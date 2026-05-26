---
name: documents/docs.cloud.google.com/iam/docs/pab-blocked-permissions
uri: https://docs.cloud.google.com/iam/docs/pab-blocked-permissions
title: Permissions that principal access boundary policies block
description: A list of permissions that are supported for principal access boundary policies.
data_source: docs.cloud.google.com
---

When principals try to access a resource that they aren't eligible to access, principal access boundary policies prevent them from using some, but not all, Identity and Access Management (IAM) permissions to access the resource.

If a principal access boundary policy blocks a permission, then IAM *enforces* principal access boundary policies for that permission. In other words, it prevents any principals that aren't eligible to access a resource from using that permission to access the resource.

If a principal access boundary policy doesn't block a permission, then principal access boundary policies have no effect on whether principals can use the permission.

Periodically, IAM adds new principal access boundary enforcement versions that can block additional permissions. Each new version can also block all of the permissions in the previous version.

This page lists the permissions that each enforcement version can block.

To learn more about principal access boundary policy version numbers, see the [principal access boundary policy overview](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#supported-permissions) .

## Default enforcement version

The default enforcement version is used for the following principal access boundary policies:

  - New policies that don't specify a version number
  - Policies that use the value `latest` for the version

The current default enforcement version is version `3` .

## Enforcement version `4`

Policies with enforcement version `4` can block all of the permissions listed in the following enforcement versions:

  - [Enforcement version `1`](https://docs.cloud.google.com/iam/docs/pab-blocked-permissions#v1)
  - [Enforcement version `2`](https://docs.cloud.google.com/iam/docs/pab-blocked-permissions#v2)
  - [Enforcement version `3`](https://docs.cloud.google.com/iam/docs/pab-blocked-permissions#v3)

Additionally, policies with the enforcement version `4` can also block all of the permissions listed in the following table.

Each row contains the following information:

  - The name of a service with permissions that principal access boundary policies can block.

  - The permissions for that service that principal access boundary policies can block.
    
    In some cases, a section of a permission name is replaced with a wildcard character ( `*` ). This format indicates that principal access boundary policies can block all permissions that match that pattern.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Permissions</th>
<th>Exceptions</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>BigQuery sharing</td>
<td><ul>
<li><code dir="ltr" translate="no">analyticshub.googleapis.com/  dataExchanges.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>BigQuery</td>
<td><ul>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  capacityCommitments.*</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  datasources.*</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  readsessions.*</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  reservations.*</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  transfers.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Deploy</td>
<td><ul>
<li><code dir="ltr" translate="no">clouddeploy.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Filestore</td>
<td><ul>
<li><code dir="ltr" translate="no">file.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Network Connectivity Center</td>
<td><ul>
<li><code dir="ltr" translate="no">networkconnectivity.googleapis.com/  groups.*</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.googleapis.com/  hubRouteTables.*</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.googleapis.com/  hubRoutes.*</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.googleapis.com/  hubs.*</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.googleapis.com/  internalRanges.*</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.googleapis.com/  policyBasedRoutes.*</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.googleapis.com/  regionalEndpoints.*</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.googleapis.com/  spokes.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Certificate Authority Service</td>
<td><ul>
<li><code dir="ltr" translate="no">privateca.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Identity and Access Management</td>
<td><ul>
<li><code dir="ltr" translate="no">iam.googleapis.com/  oauthClientCredentials.*</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  oauthClients.*</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  workforcePoolProviderKeys.*</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  workforcePoolProviders.*</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  workforcePoolSubjects.*</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  workforcePools.*</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  workloadIdentityPoolNamespaces.*</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  workloadIdentityPoolProviderKeys.*</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  workloadIdentityPoolProviders.*</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  workloadIdentityPools.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">iam.googleapis.com/*.  createPolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/*.  deletePolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/*.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/*.  updatePolicyBinding</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Live Stream</td>
<td><ul>
<li><code dir="ltr" translate="no">livestream.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Document AI</td>
<td><ul>
<li><code dir="ltr" translate="no">documentai.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Security Center Management API</td>
<td><ul>
<li><code dir="ltr" translate="no">securitycentermanagement.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Web Security Scanner</td>
<td><ul>
<li><code dir="ltr" translate="no">cloudsecurityscanner.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Security Command Center</td>
<td><ul>
<li><code dir="ltr" translate="no">securitycenter.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Quotas</td>
<td><ul>
<li><code dir="ltr" translate="no">cloudquotas.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Recommender</td>
<td><ul>
<li><code dir="ltr" translate="no">recommender.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>AlloyDB for PostgreSQL</td>
<td><ul>
<li><code dir="ltr" translate="no">alloydb.googleapis.com/*.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">alloydb.googleapis.com/databases.*</code></li>
</ul></td>
</tr>
<tr class="even">
<td>App Hub</td>
<td><ul>
<li><code dir="ltr" translate="no">apphub.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Integrations</td>
<td><ul>
<li><code dir="ltr" translate="no">integrations.googleapis.com/*.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  apigeeauthconfigs.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  apigeecertificates.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  apigeeintegrations.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  apigeeintegrationvers.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  apigeeproducts.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  apigeesfdcchannels.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  apigeesfdcinstances.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  apigeesuspensions.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  integrations.deploy</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  integrations.update</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  locations.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  securityauthconfigs.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  securityexecutions.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  securityintegrations.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  securityintegrationvers.delete</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  securityintegrationvers.deploy</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  securityintegrationvers.list</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  securityintegtemps.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  securityproducts.*</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  sfdcchannels.create</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  sfdcchannels.list</code></li>
<li><code dir="ltr" translate="no">integrations.googleapis.com/  workflows.*</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Backup for GKE</td>
<td><ul>
<li><code dir="ltr" translate="no">gkebackup.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Managed Service for Apache Airflow</td>
<td><ul>
<li><code dir="ltr" translate="no">composer.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Data Fusion</td>
<td><ul>
<li><code dir="ltr" translate="no">datafusion.googleapis.com/  instances.*</code></li>
<li><code dir="ltr" translate="no">datafusion.googleapis.com/  locations.*</code></li>
<li><code dir="ltr" translate="no">datafusion.googleapis.com/  namespaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datafusion.googleapis.com/  namespaces.  list</code></li>
<li><code dir="ltr" translate="no">datafusion.googleapis.com/  namespaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datafusion.googleapis.com/  operations.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Key Management Service</td>
<td><ul>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/*.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/locations.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Firebase Storage</td>
<td><ul>
<li><code dir="ltr" translate="no">firebasestorage.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Translation</td>
<td><ul>
<li><code dir="ltr" translate="no">cloudtranslate.googleapis.com/*.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">cloudtranslate.googleapis.com/  custommodels.*</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.googleapis.com/  translationmemories.*</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Cloud Workstations</td>
<td><ul>
<li><code dir="ltr" translate="no">workstations.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Confidential Computing</td>
<td><ul>
<li><code dir="ltr" translate="no">confidentialcomputing.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Google Cloud Contact Center as a Service</td>
<td><ul>
<li><code dir="ltr" translate="no">contactcenteraiplatform.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Database Migration Service</td>
<td><ul>
<li><code dir="ltr" translate="no">datamigration.googleapis.com/*.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">datamigration.googleapis.com/  mappingrules.*</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Dataform</td>
<td><ul>
<li><code dir="ltr" translate="no">dataform.googleapis.com/*.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">dataform.googleapis.com/  comments.*</code></li>
<li><code dir="ltr" translate="no">dataform.googleapis.com/  commentsnested.*</code></li>
<li><code dir="ltr" translate="no">dataform.googleapis.com/  commentthreads.*</code></li>
<li><code dir="ltr" translate="no">dataform.googleapis.com/  commentthreadsnested.*</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Datastream</td>
<td><ul>
<li><code dir="ltr" translate="no">datastream.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Infrastructure Manager</td>
<td><ul>
<li><code dir="ltr" translate="no">config.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Parallelstore</td>
<td><ul>
<li><code dir="ltr" translate="no">parallelstore.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Policy Simulator</td>
<td><ul>
<li><code dir="ltr" translate="no">policysimulator.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Secret Manager</td>
<td><ul>
<li><code dir="ltr" translate="no">secretmanager.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Serverless VPC Access</td>
<td><ul>
<li><code dir="ltr" translate="no">vpcaccess.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Service Usage</td>
<td><ul>
<li><code dir="ltr" translate="no">serviceusage.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Asset Inventory</td>
<td><ul>
<li><code dir="ltr" translate="no">cloudasset.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Kubernetes Metadata API</td>
<td><ul>
<li><code dir="ltr" translate="no">kubernetesmetadata.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Service Management</td>
<td><ul>
<li><code dir="ltr" translate="no">servicemanagement.googleapis.com/  consumers.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">servicemanagement.googleapis.com/  consumers.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">servicemanagement.googleapis.com/  services.  create</code></li>
<li><code dir="ltr" translate="no">servicemanagement.googleapis.com/  services.  delete</code></li>
<li><code dir="ltr" translate="no">servicemanagement.googleapis.com/  services.  get</code></li>
<li><code dir="ltr" translate="no">servicemanagement.googleapis.com/  services.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">servicemanagement.googleapis.com/  services.  list</code></li>
<li><code dir="ltr" translate="no">servicemanagement.googleapis.com/  services.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">servicemanagement.googleapis.com/  services.  update</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Backup and Disaster Recovery</td>
<td><ul>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  create</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  createForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  createForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  createForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  createForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  deleteForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  deleteForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  deleteForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  deleteForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  fetchForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  fetchForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  fetchForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  getForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  getForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  getForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  getForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanAssociations.  list</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlanRevisions.*</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupPlans.*</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  backupVaults.*</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvbackups.*</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvdataSources.  abandonBackup</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvdataSources.  fetchAccessToken</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvdataSources.  finalizeBackup</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvdataSources.  get</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvdataSources.  initiateBackup</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvdataSources.  list</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvdataSources.  remove</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvdataSources.  setInternalStatus</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvdataSources.  update</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  compute.*</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  dataSourceReferences.  fetchForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  dataSourceReferences.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  dataSourceReferences.  fetchForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  dataSourceReferences.  list</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  locations.*</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  managementServers.  create</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  managementServers.  createConnection</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  managementServers.  delete</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  managementServers.  get</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  managementServers.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  managementServers.  list</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  managementServers.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  managementServers.  update</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  operations.*</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  serviceConfig.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvbackups.  useReadOnlyForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvbackups.  useReadOnlyForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.googleapis.com/  bvbackups.  useReadOnlyForFilestoreInstance</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Sensitive Data Protection</td>
<td><ul>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  charts.*</code></li>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  columnDataProfiles.*</code></li>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  connections.*</code></li>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  deidentifyTemplates.*</code></li>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  estimates.*</code></li>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  fileStoreProfiles.*</code></li>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  inspecttemplates.*</code></li>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  jobTriggers.*</code></li>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  jobs.*</code></li>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  projectDataProfiles.*</code></li>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  storedInfoTypes.*</code></li>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  subscriptions.*</code></li>
<li><code dir="ltr" translate="no">dlp.googleapis.com/  tableDataProfiles.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Secure Source Manager</td>
<td><ul>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  branchRules.*</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  hooks.*</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  instances.  access</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  instances.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  instances.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  instances.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  instances.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  instances.  linkDeveloperConnect</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  instances.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  instances.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  issuecomments.*</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  issues.*</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  locations.*</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  operations.*</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  prcomments.*</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  pullRequests.*</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  repositories.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  repositories.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  repositories.  fetch</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  repositories.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  repositories.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  repositories.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  repositories.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.googleapis.com/  repositories.  update</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Connectors</td>
<td><ul>
<li><code dir="ltr" translate="no">connectors.googleapis.com/*.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">connectors.googleapis.com/  connections.  executeSqlQuery</code></li>
<li><code dir="ltr" translate="no">connectors.googleapis.com/  connections.  generateOpenAPISpec</code></li>
<li><code dir="ltr" translate="no">connectors.googleapis.com/  connections.  listenEvent</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Dataproc Metastore</td>
<td><ul>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  backups.*</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  databases.  delete</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  databases.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  databases.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  databases.  update</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  federations.*</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  imports.*</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  locations.*</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  operations.*</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  services.*</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  tables.  delete</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  tables.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  tables.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  tables.  update</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  federations.  use</code></li>
<li><code dir="ltr" translate="no">metastore.googleapis.com/  services.  use</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Enforcement version `3`

Policies with enforcement version `3` can block all of the permissions listed in the following enforcement versions:

  - [Enforcement version `1`](https://docs.cloud.google.com/iam/docs/pab-blocked-permissions#v1)
  - [Enforcement version `2`](https://docs.cloud.google.com/iam/docs/pab-blocked-permissions#v2)

Additionally, policies with the enforcement version `3` can also block all of the permissions listed in the following table.

Each row contains the following information:

  - The name of a service with permissions that principal access boundary policies can block.

  - The permissions for that service that principal access boundary policies can block.
    
    In some cases, a section of a permission name is replaced with a wildcard character ( `*` ). This format indicates that principal access boundary policies can block all permissions that match that pattern.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Permissions</th>
<th>Exceptions</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Essential Contacts</td>
<td><ul>
<li><code dir="ltr" translate="no">essentialcontacts.googleapis.com/  contacts.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Identity and Access Management</td>
<td><ul>
<li><code dir="ltr" translate="no">iam.googleapis.com/  denypolicies.*</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  roles.*</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  serviceAccountKeys.*</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  serviceAccounts.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">iam.googleapis.com/  serviceAccounts.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  serviceAccounts.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  serviceAccounts.  getCertificateAs</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  serviceAccounts.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.com/  serviceAccounts.  listTagBindings</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Managed Service for Apache Spark</td>
<td><ul>
<li><code dir="ltr" translate="no">dataproc.googleapis.com/  autoscalingPolicies.*</code></li>
<li><code dir="ltr" translate="no">dataproc.googleapis.com/  batches.*</code></li>
<li><code dir="ltr" translate="no">dataproc.googleapis.com/  clusters.*</code></li>
<li><code dir="ltr" translate="no">dataproc.googleapis.com/  jobs.*</code></li>
<li><code dir="ltr" translate="no">dataproc.googleapis.com/  operations.*</code></li>
<li><code dir="ltr" translate="no">dataproc.googleapis.com/  sessionTemplates.*</code></li>
<li><code dir="ltr" translate="no">dataproc.googleapis.com/  sessions.*</code></li>
<li><code dir="ltr" translate="no">dataproc.googleapis.com/  workflowTemplates.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Service Management</td>
<td><ul>
<li><code dir="ltr" translate="no">servicemanagement.googleapis.com/  services.  check</code></li>
<li><code dir="ltr" translate="no">servicemanagement.googleapis.com/  services.  report</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Bigtable</td>
<td><ul>
<li><code dir="ltr" translate="no">bigtable.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Bigtable Admin API</td>
<td><ul>
<li><code dir="ltr" translate="no">bigtableadmin.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud SQL</td>
<td><ul>
<li><code dir="ltr" translate="no">cloudsql.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Network Services</td>
<td><ul>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  endpointPolicies.*</code></li>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  gateways.*</code></li>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  grpcRoutes.*</code></li>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  httpRoutes.*</code></li>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  httpfilters.*</code></li>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  meshes.*</code></li>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  route_views.*</code></li>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  serviceBindings.*</code></li>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  serviceLbPolicies.*</code></li>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  tcpRoutes.*</code></li>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  tlsRoutes.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Service Mesh</td>
<td><ul>
<li><code dir="ltr" translate="no">trafficdirector.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Network Management API</td>
<td><ul>
<li><code dir="ltr" translate="no">networkmanagement.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Compute Engine</td>
<td><ul>
<li><code dir="ltr" translate="no">compute.googleapis.com/  addresses.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  backendBuckets.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  backendServices.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  externalVpnGateways.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  firewallPolicies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  firewalls.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  forwardingRules.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  globalAddresses.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  globalForwardingRules.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  healthChecks.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  httpHealthChecks.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  httpsHealthChecks.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  interconnectAttachments.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  interconnectLocations.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  interconnectRemoteLocations.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  interconnects.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  networks.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  packetMirrorings.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  publicAdvertisedPrefixes.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  publicDelegatedPrefixes.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  regionBackendServices.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  regionFirewallPolicies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  regionHealthChecks.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  regionSslPolicies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  regionTargetHttpProxies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  regionTargetTcpProxies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  regionUrlMaps.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  routes.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  sslPolicies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  subnetworks.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  targetGrpcProxies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  targetHttpProxies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  targetHttpsProxies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  targetInstances.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  targetPools.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  targetSslProxies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  targetTcpProxies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  targetVpnGateways.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  urlMaps.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  vpnGateways.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Artifact Registry</td>
<td><ul>
<li><code dir="ltr" translate="no">artifactregistry.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Pub/Sub</td>
<td><ul>
<li><code dir="ltr" translate="no">pubsub.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Workflows</td>
<td><ul>
<li><code dir="ltr" translate="no">workflows.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Google Distributed Cloud</td>
<td><ul>
<li><code dir="ltr" translate="no">gkeonprem.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>API Keys</td>
<td><ul>
<li><p><code dir="ltr" translate="no">apikeys.googleapis.com/  apikeys.*</code></p>
<blockquote>
<strong>Note:</strong> In the IAM v1 API, these permissions are named <code dir="ltr" translate="no">serviceusage.apiKeys.*</code> .
</blockquote></li>
<li><code dir="ltr" translate="no">apikeys.googleapis.com/  keys.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud DNS</td>
<td><ul>
<li><code dir="ltr" translate="no">dns.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Firestore</td>
<td><ul>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  backupSchedules.*</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  backups.  delete</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  backups.  get</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  backups.  list</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  databases.*</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  entities.*</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  indexes.*</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  locations.*</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  operations.*</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  userCreds.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Key Management Service</td>
<td><ul>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  autokeyConfigs.*</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  cryptoKeyVersions.  create</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  cryptoKeyVersions.  destroy</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  cryptoKeyVersions.  get</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  cryptoKeyVersions.  list</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  cryptoKeyVersions.  restore</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  cryptoKeyVersions.  update</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  cryptoKeyVersions.  useToDecrypt</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  cryptoKeyVersions.  useToEncrypt</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  cryptoKeyVersions.  useToSign</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  cryptoKeyVersions.  useToVerify</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  cryptoKeyVersions.  viewPublicKey</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  ekmConfigs.*</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  importJobs.*</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  keyHandles.*</code></li>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  keyRings.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">cloudkms.googleapis.com/  importJobs.  useToImport</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Organization Policy Service</td>
<td><ul>
<li><code dir="ltr" translate="no">orgpolicy.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Knowledge Catalog</td>
<td><ul>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  aspectTypes.*</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  datascans.*</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entries.*</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  create</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  delete</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  get</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  import</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  list</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  update</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  useContactsAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  useGenericAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  useGenericEntry</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  useOverviewAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryGroups.  useSchemaAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  entryTypes.*</code></li>
<li><code dir="ltr" translate="no">dataplex.googleapis.com/  metadataJobs.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Data Lineage API</td>
<td><ul>
<li><code dir="ltr" translate="no">datalineage.googleapis.com/  events.*</code></li>
<li><code dir="ltr" translate="no">datalineage.googleapis.com/  locations.*</code></li>
<li><code dir="ltr" translate="no">datalineage.googleapis.com/  operations.*</code></li>
<li><code dir="ltr" translate="no">datalineage.googleapis.com/  processes.*</code></li>
<li><code dir="ltr" translate="no">datalineage.googleapis.com/  runs.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>GKE Hub</td>
<td><ul>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/  fleets.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Run functions</td>
<td><ul>
<li><code dir="ltr" translate="no">cloudfunctions.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Spanner</td>
<td><ul>
<li><code dir="ltr" translate="no">spanner.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Google Kubernetes Engine</td>
<td><ul>
<li><code dir="ltr" translate="no">container.googleapis.com/*.*</code></li>
</ul></td>
<td>None</td>
</tr>
</tbody>
</table>

## Enforcement version `2`

Policies with enforcement version `2` can block all of the permissions listed in [Enforcement version `1`](https://docs.cloud.google.com/iam/docs/pab-blocked-permissions#v1) . Additionally, policies with the enforcement version `2` can also block all of the permissions listed in the following table.

Each row contains the following information:

  - The name of a service with permissions that principal access boundary policies can block.

  - The permissions for that service that principal access boundary policies can block.
    
    In some cases, a section of a permission name is replaced with a wildcard character ( `*` ). This format indicates that principal access boundary policies can block all permissions that match that pattern.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Permissions</th>
<th>Exceptions</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Access Context Manager</td>
<td><ul>
<li><code dir="ltr" translate="no">accesscontextmanager.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Artifact Analysis</td>
<td><ul>
<li><code dir="ltr" translate="no">containeranalysis.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>BigQuery</td>
<td><ul>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  rowAccessPolicies.*</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/datasets.*</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/jobs.*</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/models.*</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/routines.*</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/tables.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>BigQuery Data Policy</td>
<td><ul>
<li><code dir="ltr" translate="no">bigquerydatapolicy.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>BigQuery Data Transfer Service</td>
<td><ul>
<li><code dir="ltr" translate="no">bigquerydatatransfer.googleapis.com/  transfers.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Chrome Enterprise Premium</td>
<td><ul>
<li><code dir="ltr" translate="no">beyondcorp.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Asset Inventory</td>
<td><ul>
<li><code dir="ltr" translate="no">cloudasset.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Billing</td>
<td><ul>
<li><code dir="ltr" translate="no">billing.googleapis.com/budgets.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Build</td>
<td><ul>
<li><code dir="ltr" translate="no">cloudbuild.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Monitoring</td>
<td><ul>
<li><code dir="ltr" translate="no">monitoring.googleapis.com/*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">monitoring.googleapis.com/  metricsScopes.  link</code></li>
<li><code dir="ltr" translate="no">monitoring.googleapis.com/  timeSeries.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Cloud Service Mesh</td>
<td><ul>
<li><code dir="ltr" translate="no">meshconfig.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Storage</td>
<td><ul>
<li><code dir="ltr" translate="no">storage.googleapis.com/  bucketOperations.*</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/  buckets.*</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/  managedFolders.*</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/  multipartUploads.*</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/folders.*</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/hmacKeys.*</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/objects.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Trace</td>
<td><ul>
<li><code dir="ltr" translate="no">cloudtrace.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Compute Engine</td>
<td><ul>
<li><code dir="ltr" translate="no">compute.googleapis.com/  networkAttachments.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  networkEdgeSecurityServices.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  regionSecurityPolicies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  securityPolicies.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/  serviceAttachments.*</code></li>
<li><code dir="ltr" translate="no">compute.googleapis.com/routers.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Firebase Security Rules</td>
<td><ul>
<li><code dir="ltr" translate="no">firebaserules.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>GKE Multi-Cloud</td>
<td><ul>
<li><code dir="ltr" translate="no">gkemulticloud.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Identity-Aware Proxy</td>
<td><ul>
<li><code dir="ltr" translate="no">iap.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Memorystore for Redis</td>
<td><ul>
<li><code dir="ltr" translate="no">redis.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Network Management API</td>
<td><ul>
<li><code dir="ltr" translate="no">networkmanagement.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Network Services</td>
<td><ul>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  edgeCacheKeysets.*</code></li>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  edgeCacheOrigins.*</code></li>
<li><code dir="ltr" translate="no">networkservices.googleapis.com/  edgeCacheServices.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>reCAPTCHA</td>
<td><ul>
<li><code dir="ltr" translate="no">recaptchaenterprise.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Resource Manager</td>
<td><ul>
<li><code dir="ltr" translate="no">cloudresourcemanager.googleapis.com/*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">cloudresourcemanager.googleapis.com/  *.  createPolicyBinding</code></li>
<li><code dir="ltr" translate="no">cloudresourcemanager.googleapis.com/  *.  deletePolicyBinding</code></li>
<li><code dir="ltr" translate="no">cloudresourcemanager.googleapis.com/  *.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">cloudresourcemanager.googleapis.com/  *.  updatePolicyBinding</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Video Stitcher API</td>
<td><ul>
<li><code dir="ltr" translate="no">videostitcher.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
</tbody>
</table>

## Enforcement version `1`

The following table lists the permissions that principal access boundary policies with enforcement version `1` can block.

Each row contains the following information:

  - The name of a service with permissions that principal access boundary policies can block.

  - The permissions for that service that principal access boundary policies can block.
    
    In some cases, a section of a permission name is replaced with a wildcard character ( `*` ). This format indicates that principal access boundary policies can block all permissions that match that pattern.

  - The permissions for the service that principal access boundary can't block, even if those permissions match one of the supported permission patterns.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Permissions</th>
<th>Exceptions</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Access Approval</td>
<td><ul>
<li><code dir="ltr" translate="no">accessapproval.googleapis.com/  requests.  list</code></li>
<li><code dir="ltr" translate="no">accessapproval.googleapis.com/  serviceaccounts.  get</code></li>
<li><code dir="ltr" translate="no">accessapproval.googleapis.com/settings.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Access Context Manager</td>
<td><ul>
<li><code dir="ltr" translate="no">accesscontextmanager.googleapis.com/*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">accesscontextmanager.googleapis.com/  gcpUserAccessBindings.*</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>BigQuery</td>
<td><ul>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  datasets.  create</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  datasets.  delete</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  datasets.  get</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  datasets.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  datasets.  update</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  jobs.  create</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  jobs.  delete</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  jobs.  list</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  jobs.get</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  models.  create</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  models.  delete</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  models.  list</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  models.  updateMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  routines.  create</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  routines.  delete</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  routines.  list</code></li>
<li><code dir="ltr" translate="no">bigquery.googleapis.com/  routines.  update</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Binary Authorization</td>
<td><ul>
<li><code dir="ltr" translate="no">binaryauthorization.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Logging</td>
<td><ul>
<li><code dir="ltr" translate="no">logging.googleapis.com/  logEntries.  create</code></li>
<li><code dir="ltr" translate="no">logging.googleapis.com/logMetrics.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Run</td>
<td><ul>
<li><code dir="ltr" translate="no">run.googleapis.com/  authorizeddomains.*</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/  configurations.  get</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/  configurations.  list</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/  domainmappings.*</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/  services.  create</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/  services.  delete</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/  services.  get</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/  services.  list</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/  services.  update</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/executions.*</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/jobs.create</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/jobs.delete</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/jobs.get</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/jobs.list</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/jobs.run</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/revisions.*</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/routes.get</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/routes.list</code></li>
<li><code dir="ltr" translate="no">run.googleapis.com/tasks.*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Storage</td>
<td><ul>
<li><code dir="ltr" translate="no">storage.googleapis.com/  buckets.  get</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/  buckets.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/  buckets.  list</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/  buckets.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/  buckets.  update</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/  hmacKeys.  update</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/  objects.  delete</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/  objects.  get</code></li>
<li><code dir="ltr" translate="no">storage.googleapis.com/  objects.  setRetention</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Dataflow</td>
<td><ul>
<li><code dir="ltr" translate="no">dataflow.googleapis.com/  messages.  list</code></li>
<li><code dir="ltr" translate="no">dataflow.googleapis.com/  metrics.  get</code></li>
<li><code dir="ltr" translate="no">dataflow.googleapis.com/  snapshots.  list</code></li>
<li><code dir="ltr" translate="no">dataflow.googleapis.com/  workItems.*</code></li>
<li><code dir="ltr" translate="no">dataflow.googleapis.com/jobs.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">dataflow.googleapis.com/  jobs.  snapshot</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Firestore</td>
<td><ul>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  databases.  create</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  databases.  delete</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  databases.  get</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  databases.  getMetadata</code></li>
<li><code dir="ltr" translate="no">datastore.googleapis.com/  databases.  list</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Firebase Security Rules</td>
<td><ul>
<li><code dir="ltr" translate="no">firebaserules.googleapis.com/*</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>GKE Hub</td>
<td><ul>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/  membershipbindings.*</code></li>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/  rbacrolebindings.*</code></li>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/features.*</code></li>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/fleet.create</code></li>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/fleet.get</code></li>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/fleet.patch</code></li>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/locations.*</code></li>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/memberships.*</code></li>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/scopes.*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/*.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/*.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/*.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">gkehub.googleapis.com/*.  listTagBindings</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Pub/Sub</td>
<td><ul>
<li><code dir="ltr" translate="no">pubsub.googleapis.com/*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">pubsub.googleapis.com/*.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.googleapis.com/*.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.googleapis.com/  schemas.  delete</code></li>
<li><code dir="ltr" translate="no">pubsub.googleapis.com/  schemas.  validate</code></li>
<li><code dir="ltr" translate="no">pubsub.googleapis.com/  subscriptions.  consume</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Memorystore for Redis</td>
<td><ul>
<li><code dir="ltr" translate="no">redis.googleapis.com/  instances.  create</code></li>
<li><code dir="ltr" translate="no">redis.googleapis.com/  instances.  delete</code></li>
<li><code dir="ltr" translate="no">redis.googleapis.com/  instances.  failover</code></li>
<li><code dir="ltr" translate="no">redis.googleapis.com/  instances.  get</code></li>
<li><code dir="ltr" translate="no">redis.googleapis.com/  instances.  getAuthString</code></li>
<li><code dir="ltr" translate="no">redis.googleapis.com/  instances.  list</code></li>
<li><code dir="ltr" translate="no">redis.googleapis.com/  instances.  update</code></li>
<li><code dir="ltr" translate="no">redis.googleapis.com/  instances.  upgrade</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Gemini Enterprise Agent Platform</td>
<td><ul>
<li><code dir="ltr" translate="no">aiplatform.googleapis.com/*</code></li>
</ul></td>
<td><ul>
<li><code dir="ltr" translate="no">aiplatform.googleapis.com/  operations.*</code></li>
</ul></td>
</tr>
</tbody>
</table>
