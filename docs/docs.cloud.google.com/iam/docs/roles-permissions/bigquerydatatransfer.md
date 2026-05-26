---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer
title: BigQuery Data Transfer Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for BigQuery Data Transfer Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## BigQuery Data Transfer Service roles

BigQuery Data Transfer Service offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="bigquerydatatransfer.serviceAgent" class="role-title add-link" data-text="BigQuery Data Transfer Service Agent" tabindex="-1">BigQuery Data Transfer Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</p>
<p>Gives BigQuery Data Transfer Service access to start BigQuery jobs in consumer project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.config.get</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.delegate</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">compute.networkAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  update</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">dataform.folders.create</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useContactsAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataProfileAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useDatabaseDataPolicyAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useMySQLConnectorTypes</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useOracleConnectorTypes</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useOverviewAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  usePostgreSQLConnectorTypes</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLAccessAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLServerConnectorTypes</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLTriggersAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSecondaryIndexesAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useStorageAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.metadataJobs.create</code></p>
<p><code dir="ltr" translate="no">dataplex.metadataJobs.get</code></p>
<p><code dir="ltr" translate="no">dataplex.metadataJobs.list</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## BigQuery Data Transfer Service permissions

There are no IAM permissions for this service.
