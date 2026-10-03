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
<td>BigQuery Data Transfer Service Agent
<p>( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</p>
<p>Gives BigQuery Data Transfer Service access to start BigQuery jobs in consumer project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>bigquery.config.get</code></p>
<p><code>bigquery.connections.delegate</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>compute.networkAttachments.get</code></p>
<p><code>compute. networkAttachments. update</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>dataform.folders.create</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.repositories.create</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataplex.entryGroups.get</code></p>
<p><code>dataplex. entryGroups. useContactsAspect</code></p>
<p><code>dataplex. entryGroups. useDataProfileAspect</code></p>
<p><code>dataplex. entryGroups. useDatabaseDataPolicyAspect</code></p>
<p><code>dataplex. entryGroups. useManagedConnectorTypes</code></p>
<p><code>dataplex. entryGroups. useMySQLConnectorTypes</code></p>
<p><code>dataplex. entryGroups. useOracleConnectorTypes</code></p>
<p><code>dataplex. entryGroups. useOverviewAspect</code></p>
<p><code>dataplex. entryGroups. usePostgreSQLConnectorTypes</code></p>
<p><code>dataplex. entryGroups. useSQLAccessAspect</code></p>
<p><code>dataplex. entryGroups. useSQLServerConnectorTypes</code></p>
<p><code>dataplex. entryGroups. useSQLTriggersAspect</code></p>
<p><code>dataplex. entryGroups. useSchemaAspect</code></p>
<p><code>dataplex. entryGroups. useSecondaryIndexesAspect</code></p>
<p><code>dataplex. entryGroups. useStorageAspect</code></p>
<p><code>dataplex.metadataJobs.create</code></p>
<p><code>dataplex.metadataJobs.get</code></p>
<p><code>dataplex.metadataJobs.list</code></p>
<p><code>geminidataanalytics. locations. chat</code></p>
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## BigQuery Data Transfer Service permissions

There are no IAM permissions for this service.
