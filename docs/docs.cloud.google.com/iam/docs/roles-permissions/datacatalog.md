---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/datacatalog
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog
title: Data Catalog roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Data Catalog. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Data Catalog roles

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
<td>Data Catalog Admin
<p>( <code>roles/ datacatalog.admin</code> )</p>
<p>Full access to all DataCatalog resources</p></td>
<td><p><code>bigquery.connections.get</code></p>
<p><code>bigquery.connections.updateTag</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.datasets.updateTag</code></p>
<p><code>bigquery.models.getMetadata</code></p>
<p><code>bigquery.models.updateTag</code></p>
<p><code>bigquery.routines.get</code></p>
<p><code>bigquery.routines.updateTag</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.updateTag</code></p>
<p><code>datacatalog.catalogs.searchAll</code></p>
<p><code>datacatalog. categories. getIamPolicy</code></p>
<p><code>datacatalog. categories. setIamPolicy</code></p>
<p><code>datacatalog.entries.*</code></p>
<ul>
<li><code>datacatalog.entries.create</code></li>
<li><code>datacatalog. entries. createGlossary</code></li>
<li><code>datacatalog. entries. createGlossaryCategory</code></li>
<li><code>datacatalog. entries. createGlossaryTerm</code></li>
<li><code>datacatalog.entries.delete</code></li>
<li><code>datacatalog. entries. deleteGlossary</code></li>
<li><code>datacatalog. entries. deleteGlossaryCategory</code></li>
<li><code>datacatalog. entries. deleteGlossaryTerm</code></li>
<li><code>datacatalog.entries.get</code></li>
<li><code>datacatalog. entries. getIamPolicy</code></li>
<li><code>datacatalog.entries.list</code></li>
<li><code>datacatalog. entries. setIamPolicy</code></li>
<li><code>datacatalog.entries.update</code></li>
<li><code>datacatalog. entries. updateContacts</code></li>
<li><code>datacatalog. entries. updateGlossary</code></li>
<li><code>datacatalog. entries. updateGlossaryCategory</code></li>
<li><code>datacatalog. entries. updateGlossaryTerm</code></li>
<li><code>datacatalog. entries. updateOverview</code></li>
<li><code>datacatalog.entries.updateTag</code></li>
</ul>
<p><code>datacatalog.entryGroups.*</code></p>
<ul>
<li><code>datacatalog.entryGroups.create</code></li>
<li><code>datacatalog.entryGroups.delete</code></li>
<li><code>datacatalog.entryGroups.get</code></li>
<li><code>datacatalog. entryGroups. getIamPolicy</code></li>
<li><code>datacatalog.entryGroups.list</code></li>
<li><code>datacatalog. entryGroups. setIamPolicy</code></li>
<li><code>datacatalog.entryGroups.update</code></li>
<li><code>datacatalog. entryGroups. updateTag</code></li>
</ul>
<p><code>datacatalog.migrationConfig.*</code></p>
<ul>
<li><code>datacatalog. migrationConfig. get</code></li>
<li><code>datacatalog. migrationConfig. set</code></li>
</ul>
<p><code>datacatalog.operations.list</code></p>
<p><code>datacatalog.relationships.*</code></p>
<ul>
<li><code>datacatalog. relationships. create</code></li>
<li><code>datacatalog. relationships. createBelongsTo</code></li>
<li><code>datacatalog. relationships. createIsDescribedBy</code></li>
<li><code>datacatalog. relationships. createIsRelatedTo</code></li>
<li><code>datacatalog. relationships. createIsSynonymousTo</code></li>
<li><code>datacatalog. relationships. delete</code></li>
<li><code>datacatalog. relationships. deleteBelongsTo</code></li>
<li><code>datacatalog. relationships. deleteIsDescribedBy</code></li>
<li><code>datacatalog. relationships. deleteIsRelatedTo</code></li>
<li><code>datacatalog. relationships. deleteIsSynonymousTo</code></li>
<li><code>datacatalog.relationships.list</code></li>
</ul>
<p><code>datacatalog.tagTemplates.*</code></p>
<ul>
<li><code>datacatalog. tagTemplates. create</code></li>
<li><code>datacatalog. tagTemplates. delete</code></li>
<li><code>datacatalog.tagTemplates.get</code></li>
<li><code>datacatalog. tagTemplates. getIamPolicy</code></li>
<li><code>datacatalog. tagTemplates. getTag</code></li>
<li><code>datacatalog. tagTemplates. setIamPolicy</code></li>
<li><code>datacatalog. tagTemplates. update</code></li>
<li><code>datacatalog.tagTemplates.use</code></li>
</ul>
<p><code>datacatalog.taxonomies.*</code></p>
<ul>
<li><code>datacatalog.taxonomies.create</code></li>
<li><code>datacatalog.taxonomies.delete</code></li>
<li><code>datacatalog.taxonomies.get</code></li>
<li><code>datacatalog. taxonomies. getIamPolicy</code></li>
<li><code>datacatalog.taxonomies.list</code></li>
<li><code>datacatalog. taxonomies. setIamPolicy</code></li>
<li><code>datacatalog.taxonomies.update</code></li>
</ul>
<p><code>dataplex.aspectTypes.*</code></p>
<ul>
<li><code>dataplex.aspectTypes.create</code></li>
<li><code>dataplex.aspectTypes.delete</code></li>
<li><code>dataplex.aspectTypes.get</code></li>
<li><code>dataplex. aspectTypes. getIamPolicy</code></li>
<li><code>dataplex.aspectTypes.list</code></li>
<li><code>dataplex. aspectTypes. setIamPolicy</code></li>
<li><code>dataplex.aspectTypes.update</code></li>
<li><code>dataplex.aspectTypes.use</code></li>
</ul>
<p><code>dataplex. changeRequests. adminDelete</code></p>
<p><code>dataplex.changeRequests.delete</code></p>
<p><code>dataplex.changeRequests.get</code></p>
<p><code>dataplex.changeRequests.list</code></p>
<p><code>dataplex.changeRequests.use</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.entries.*</code></p>
<ul>
<li><code>dataplex.entries.create</code></li>
<li><code>dataplex.entries.delete</code></li>
<li><code>dataplex.entries.get</code></li>
<li><code>dataplex.entries.getData</code></li>
<li><code>dataplex.entries.link</code></li>
<li><code>dataplex.entries.list</code></li>
<li><code>dataplex.entries.update</code></li>
</ul>
<p><code>dataplex.entryGroups.*</code></p>
<ul>
<li><code>dataplex.entryGroups.create</code></li>
<li><code>dataplex. entryGroups. createTagBinding</code></li>
<li><code>dataplex.entryGroups.delete</code></li>
<li><code>dataplex. entryGroups. deleteTagBinding</code></li>
<li><code>dataplex.entryGroups.export</code></li>
<li><code>dataplex.entryGroups.get</code></li>
<li><code>dataplex. entryGroups. getIamPolicy</code></li>
<li><code>dataplex.entryGroups.import</code></li>
<li><code>dataplex.entryGroups.list</code></li>
<li><code>dataplex. entryGroups. listEffectiveTags</code></li>
<li><code>dataplex. entryGroups. listTagBindings</code></li>
<li><code>dataplex. entryGroups. requestChanges</code></li>
<li><code>dataplex. entryGroups. setIamPolicy</code></li>
<li><code>dataplex.entryGroups.update</code></li>
<li><code>dataplex. entryGroups. useContactsAspect</code></li>
<li><code>dataplex. entryGroups. useContextAspect</code></li>
<li><code>dataplex. entryGroups. useContextEntry</code></li>
<li><code>dataplex. entryGroups. useContextEntryLink</code></li>
<li><code>dataplex. entryGroups. useDataProfileAspect</code></li>
<li><code>dataplex. entryGroups. useDataQualityRuleTemplateAspect</code></li>
<li><code>dataplex. entryGroups. useDataQualityRuleTemplateEntry</code></li>
<li><code>dataplex. entryGroups. useDataQualityScorecardAspect</code></li>
<li><code>dataplex. entryGroups. useDataRulesAspect</code></li>
<li><code>dataplex. entryGroups. useDatabaseDataPolicyAspect</code></li>
<li><code>dataplex. entryGroups. useDefinitionEntryLink</code></li>
<li><code>dataplex. entryGroups. useDescriptionsAspect</code></li>
<li><code>dataplex. entryGroups. useGenericAspect</code></li>
<li><code>dataplex. entryGroups. useGenericEntry</code></li>
<li><code>dataplex. entryGroups. useGraphProfileAspect</code></li>
<li><code>dataplex. entryGroups. useManagedConnectorTypes</code></li>
<li><code>dataplex. entryGroups. useMySQLConnectorTypes</code></li>
<li><code>dataplex. entryGroups. useOracleConnectorTypes</code></li>
<li><code>dataplex. entryGroups. useOverviewAspect</code></li>
<li><code>dataplex. entryGroups. usePostgreSQLConnectorTypes</code></li>
<li><code>dataplex. entryGroups. useQueriesAspect</code></li>
<li><code>dataplex. entryGroups. useRefreshCadenceAspect</code></li>
<li><code>dataplex. entryGroups. useRelatedEntryLink</code></li>
<li><code>dataplex. entryGroups. useSQLAccessAspect</code></li>
<li><code>dataplex. entryGroups. useSQLServerConnectorTypes</code></li>
<li><code>dataplex. entryGroups. useSQLTriggersAspect</code></li>
<li><code>dataplex. entryGroups. useSchemaAspect</code></li>
<li><code>dataplex. entryGroups. useSchemaJoinAspect</code></li>
<li><code>dataplex. entryGroups. useSchemaJoinEntryLink</code></li>
<li><code>dataplex. entryGroups. useSecondaryIndexesAspect</code></li>
<li><code>dataplex. entryGroups. useStorageAspect</code></li>
<li><code>dataplex. entryGroups. useSynonymEntryLink</code></li>
</ul>
<p><code>dataplex.entryLinkTypes.*</code></p>
<ul>
<li><code>dataplex.entryLinkTypes.create</code></li>
<li><code>dataplex.entryLinkTypes.delete</code></li>
<li><code>dataplex.entryLinkTypes.get</code></li>
<li><code>dataplex. entryLinkTypes. getIamPolicy</code></li>
<li><code>dataplex.entryLinkTypes.list</code></li>
<li><code>dataplex. entryLinkTypes. setIamPolicy</code></li>
<li><code>dataplex.entryLinkTypes.update</code></li>
<li><code>dataplex.entryLinkTypes.use</code></li>
</ul>
<p><code>dataplex.entryLinks.*</code></p>
<ul>
<li><code>dataplex.entryLinks.create</code></li>
<li><code>dataplex.entryLinks.delete</code></li>
<li><code>dataplex.entryLinks.get</code></li>
<li><code>dataplex.entryLinks.reference</code></li>
<li><code>dataplex.entryLinks.update</code></li>
</ul>
<p><code>dataplex.entryTypes.*</code></p>
<ul>
<li><code>dataplex.entryTypes.create</code></li>
<li><code>dataplex. entryTypes. createTagBinding</code></li>
<li><code>dataplex.entryTypes.delete</code></li>
<li><code>dataplex. entryTypes. deleteTagBinding</code></li>
<li><code>dataplex.entryTypes.get</code></li>
<li><code>dataplex. entryTypes. getIamPolicy</code></li>
<li><code>dataplex.entryTypes.list</code></li>
<li><code>dataplex. entryTypes. listEffectiveTags</code></li>
<li><code>dataplex. entryTypes. listTagBindings</code></li>
<li><code>dataplex. entryTypes. setIamPolicy</code></li>
<li><code>dataplex.entryTypes.update</code></li>
<li><code>dataplex.entryTypes.use</code></li>
</ul>
<p><code>dataplex.glossaries.*</code></p>
<ul>
<li><code>dataplex.glossaries.create</code></li>
<li><code>dataplex.glossaries.delete</code></li>
<li><code>dataplex.glossaries.get</code></li>
<li><code>dataplex. glossaries. getIamPolicy</code></li>
<li><code>dataplex.glossaries.import</code></li>
<li><code>dataplex.glossaries.list</code></li>
<li><code>dataplex. glossaries. requestChanges</code></li>
<li><code>dataplex. glossaries. setIamPolicy</code></li>
<li><code>dataplex.glossaries.update</code></li>
</ul>
<p><code>dataplex.glossaryCategories.*</code></p>
<ul>
<li><code>dataplex. glossaryCategories. create</code></li>
<li><code>dataplex. glossaryCategories. delete</code></li>
<li><code>dataplex. glossaryCategories. get</code></li>
<li><code>dataplex. glossaryCategories. list</code></li>
<li><code>dataplex. glossaryCategories. update</code></li>
</ul>
<p><code>dataplex.glossaryTerms.*</code></p>
<ul>
<li><code>dataplex.glossaryTerms.create</code></li>
<li><code>dataplex.glossaryTerms.delete</code></li>
<li><code>dataplex.glossaryTerms.get</code></li>
<li><code>dataplex.glossaryTerms.list</code></li>
<li><code>dataplex.glossaryTerms.update</code></li>
<li><code>dataplex.glossaryTerms.use</code></li>
</ul>
<p><code>dataplex.locations.*</code></p>
<ul>
<li><code>dataplex.locations.get</code></li>
<li><code>dataplex.locations.list</code></li>
</ul>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.updateTag</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Data Catalog Editor
<p>( <code>roles/ datacatalog.editor</code> )</p>
<p>Editor role for Data Catalog</p></td>
<td><p><code>bigquery.connections.get</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.models.getMetadata</code></p>
<p><code>bigquery.routines.get</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>datacatalog.catalogs.searchAll</code></p>
<p><code>datacatalog. categories. getIamPolicy</code></p>
<p><code>datacatalog.entries.create</code></p>
<p><code>datacatalog. entries. createGlossary</code></p>
<p><code>datacatalog. entries. createGlossaryCategory</code></p>
<p><code>datacatalog. entries. createGlossaryTerm</code></p>
<p><code>datacatalog.entries.delete</code></p>
<p><code>datacatalog. entries. deleteGlossary</code></p>
<p><code>datacatalog. entries. deleteGlossaryCategory</code></p>
<p><code>datacatalog. entries. deleteGlossaryTerm</code></p>
<p><code>datacatalog.entries.get</code></p>
<p><code>datacatalog. entries. getIamPolicy</code></p>
<p><code>datacatalog.entries.list</code></p>
<p><code>datacatalog.entries.update</code></p>
<p><code>datacatalog. entries. updateContacts</code></p>
<p><code>datacatalog. entries. updateGlossary</code></p>
<p><code>datacatalog. entries. updateGlossaryCategory</code></p>
<p><code>datacatalog. entries. updateGlossaryTerm</code></p>
<p><code>datacatalog. entries. updateOverview</code></p>
<p><code>datacatalog.entries.updateTag</code></p>
<p><code>datacatalog.entryGroups.create</code></p>
<p><code>datacatalog.entryGroups.delete</code></p>
<p><code>datacatalog.entryGroups.get</code></p>
<p><code>datacatalog. entryGroups. getIamPolicy</code></p>
<p><code>datacatalog.entryGroups.list</code></p>
<p><code>datacatalog.entryGroups.update</code></p>
<p><code>datacatalog. entryGroups. updateTag</code></p>
<p><code>datacatalog.migrationConfig.*</code></p>
<ul>
<li><code>datacatalog. migrationConfig. get</code></li>
<li><code>datacatalog. migrationConfig. set</code></li>
</ul>
<p><code>datacatalog.operations.list</code></p>
<p><code>datacatalog.relationships.*</code></p>
<ul>
<li><code>datacatalog. relationships. create</code></li>
<li><code>datacatalog. relationships. createBelongsTo</code></li>
<li><code>datacatalog. relationships. createIsDescribedBy</code></li>
<li><code>datacatalog. relationships. createIsRelatedTo</code></li>
<li><code>datacatalog. relationships. createIsSynonymousTo</code></li>
<li><code>datacatalog. relationships. delete</code></li>
<li><code>datacatalog. relationships. deleteBelongsTo</code></li>
<li><code>datacatalog. relationships. deleteIsDescribedBy</code></li>
<li><code>datacatalog. relationships. deleteIsRelatedTo</code></li>
<li><code>datacatalog. relationships. deleteIsSynonymousTo</code></li>
<li><code>datacatalog.relationships.list</code></li>
</ul>
<p><code>datacatalog. tagTemplates. create</code></p>
<p><code>datacatalog. tagTemplates. delete</code></p>
<p><code>datacatalog.tagTemplates.get</code></p>
<p><code>datacatalog. tagTemplates. getIamPolicy</code></p>
<p><code>datacatalog. tagTemplates. getTag</code></p>
<p><code>datacatalog. tagTemplates. update</code></p>
<p><code>datacatalog.tagTemplates.use</code></p>
<p><code>datacatalog.taxonomies.get</code></p>
<p><code>datacatalog. taxonomies. getIamPolicy</code></p>
<p><code>datacatalog.taxonomies.list</code></p>
<p><code>dataplex.aspectTypes.get</code></p>
<p><code>dataplex. aspectTypes. getIamPolicy</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex.changeRequests.get</code></p>
<p><code>dataplex.changeRequests.list</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.entries.get</code></p>
<p><code>dataplex.entries.list</code></p>
<p><code>dataplex.entryGroups.get</code></p>
<p><code>dataplex. entryGroups. getIamPolicy</code></p>
<p><code>dataplex.entryGroups.list</code></p>
<p><code>dataplex. entryGroups. listEffectiveTags</code></p>
<p><code>dataplex. entryGroups. listTagBindings</code></p>
<p><code>dataplex. entryGroups. requestChanges</code></p>
<p><code>dataplex.entryLinkTypes.get</code></p>
<p><code>dataplex. entryLinkTypes. getIamPolicy</code></p>
<p><code>dataplex.entryLinkTypes.list</code></p>
<p><code>dataplex.entryLinks.get</code></p>
<p><code>dataplex.entryTypes.get</code></p>
<p><code>dataplex. entryTypes. getIamPolicy</code></p>
<p><code>dataplex.entryTypes.list</code></p>
<p><code>dataplex. entryTypes. listEffectiveTags</code></p>
<p><code>dataplex. entryTypes. listTagBindings</code></p>
<p><code>dataplex.glossaries.get</code></p>
<p><code>dataplex. glossaries. getIamPolicy</code></p>
<p><code>dataplex.glossaries.list</code></p>
<p><code>dataplex. glossaries. requestChanges</code></p>
<p><code>dataplex. glossaryCategories. get</code></p>
<p><code>dataplex. glossaryCategories. list</code></p>
<p><code>dataplex.glossaryTerms.get</code></p>
<p><code>dataplex.glossaryTerms.list</code></p>
<p><code>dataplex.locations.*</code></p>
<ul>
<li><code>dataplex.locations.get</code></li>
<li><code>dataplex.locations.list</code></li>
</ul>
<p><code>dataplex.projects.search</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Data Catalog Viewer
<p>( <code>roles/ datacatalog.viewer</code> )</p>
<p>Provides metadata read access to catalogued Google Cloud assets for BigQuery and Pub/Sub</p></td>
<td><p><code>bigquery.connections.get</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.models.getMetadata</code></p>
<p><code>bigquery.routines.get</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>datacatalog.entries.get</code></p>
<p><code>datacatalog.entries.list</code></p>
<p><code>datacatalog.entryGroups.get</code></p>
<p><code>datacatalog.entryGroups.list</code></p>
<p><code>datacatalog. migrationConfig. get</code></p>
<p><code>datacatalog.operations.list</code></p>
<p><code>datacatalog.relationships.list</code></p>
<p><code>datacatalog.tagTemplates.get</code></p>
<p><code>datacatalog. tagTemplates. getTag</code></p>
<p><code>datacatalog.taxonomies.get</code></p>
<p><code>datacatalog.taxonomies.list</code></p>
<p><code>dataplex.aspectTypes.get</code></p>
<p><code>dataplex. aspectTypes. getIamPolicy</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex.changeRequests.get</code></p>
<p><code>dataplex.changeRequests.list</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.entries.get</code></p>
<p><code>dataplex.entries.list</code></p>
<p><code>dataplex.entryGroups.get</code></p>
<p><code>dataplex. entryGroups. getIamPolicy</code></p>
<p><code>dataplex.entryGroups.list</code></p>
<p><code>dataplex. entryGroups. listEffectiveTags</code></p>
<p><code>dataplex. entryGroups. listTagBindings</code></p>
<p><code>dataplex. entryGroups. requestChanges</code></p>
<p><code>dataplex.entryLinkTypes.get</code></p>
<p><code>dataplex. entryLinkTypes. getIamPolicy</code></p>
<p><code>dataplex.entryLinkTypes.list</code></p>
<p><code>dataplex.entryLinks.get</code></p>
<p><code>dataplex.entryTypes.get</code></p>
<p><code>dataplex. entryTypes. getIamPolicy</code></p>
<p><code>dataplex.entryTypes.list</code></p>
<p><code>dataplex. entryTypes. listEffectiveTags</code></p>
<p><code>dataplex. entryTypes. listTagBindings</code></p>
<p><code>dataplex.glossaries.get</code></p>
<p><code>dataplex. glossaries. getIamPolicy</code></p>
<p><code>dataplex.glossaries.list</code></p>
<p><code>dataplex. glossaries. requestChanges</code></p>
<p><code>dataplex. glossaryCategories. get</code></p>
<p><code>dataplex. glossaryCategories. list</code></p>
<p><code>dataplex.glossaryTerms.get</code></p>
<p><code>dataplex.glossaryTerms.list</code></p>
<p><code>dataplex.locations.*</code></p>
<ul>
<li><code>dataplex.locations.get</code></li>
<li><code>dataplex.locations.list</code></li>
</ul>
<p><code>dataplex.projects.search</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Policy Tag Admin
<p>( <code>roles/ datacatalog.categoryAdmin</code> )</p>
<p>Manage taxonomies</p></td>
<td><p><code>datacatalog. categories. getIamPolicy</code></p>
<p><code>datacatalog. categories. setIamPolicy</code></p>
<p><code>datacatalog.taxonomies.*</code></p>
<ul>
<li><code>datacatalog.taxonomies.create</code></li>
<li><code>datacatalog.taxonomies.delete</code></li>
<li><code>datacatalog.taxonomies.get</code></li>
<li><code>datacatalog. taxonomies. getIamPolicy</code></li>
<li><code>datacatalog.taxonomies.list</code></li>
<li><code>datacatalog. taxonomies. setIamPolicy</code></li>
<li><code>datacatalog.taxonomies.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Fine-Grained Reader
<p>( <code>roles/ datacatalog.categoryFineGrainedReader</code> )</p>
<p>Read access to sub-resources tagged by a policy tag, for example, BigQuery columns</p></td>
<td><p><code>datacatalog. categories. fineGrainedGet</code></p></td>
</tr>
<tr class="even">
<td>DataCatalog Data Steward <sup>Beta</sup>
<p>( <code>roles/ datacatalog.dataSteward</code> )</p>
<p>Can update overview and data steward fields</p></td>
<td><p><code>datacatalog.entries.get</code></p>
<p><code>datacatalog.entries.list</code></p>
<p><code>datacatalog. entries. updateContacts</code></p>
<p><code>datacatalog. entries. updateOverview</code></p>
<p><code>datacatalog.entryGroups.get</code></p>
<p><code>datacatalog. migrationConfig. get</code></p>
<p><code>datacatalog.relationships.list</code></p>
<p><code>dataplex.entries.get</code></p>
<p><code>dataplex.entries.list</code></p>
<p><code>dataplex.entryGroups.get</code></p>
<p><code>dataplex. entryGroups. useContactsAspect</code></p>
<p><code>dataplex. entryGroups. useOverviewAspect</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>DataCatalog EntryGroup Creator
<p>( <code>roles/ datacatalog.entryGroupCreator</code> )</p>
<p>Can create new entryGroups</p></td>
<td><p><code>datacatalog.entryGroups.create</code></p>
<p><code>datacatalog.entryGroups.get</code></p>
<p><code>datacatalog.entryGroups.list</code></p>
<p><code>dataplex.entryGroups.create</code></p>
<p><code>dataplex.entryGroups.get</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>DataCatalog EntryGroup Owner
<p>( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p>Full access to entryGroups</p></td>
<td><p><code>datacatalog.entries.*</code></p>
<ul>
<li><code>datacatalog.entries.create</code></li>
<li><code>datacatalog. entries. createGlossary</code></li>
<li><code>datacatalog. entries. createGlossaryCategory</code></li>
<li><code>datacatalog. entries. createGlossaryTerm</code></li>
<li><code>datacatalog.entries.delete</code></li>
<li><code>datacatalog. entries. deleteGlossary</code></li>
<li><code>datacatalog. entries. deleteGlossaryCategory</code></li>
<li><code>datacatalog. entries. deleteGlossaryTerm</code></li>
<li><code>datacatalog.entries.get</code></li>
<li><code>datacatalog. entries. getIamPolicy</code></li>
<li><code>datacatalog.entries.list</code></li>
<li><code>datacatalog. entries. setIamPolicy</code></li>
<li><code>datacatalog.entries.update</code></li>
<li><code>datacatalog. entries. updateContacts</code></li>
<li><code>datacatalog. entries. updateGlossary</code></li>
<li><code>datacatalog. entries. updateGlossaryCategory</code></li>
<li><code>datacatalog. entries. updateGlossaryTerm</code></li>
<li><code>datacatalog. entries. updateOverview</code></li>
<li><code>datacatalog.entries.updateTag</code></li>
</ul>
<p><code>datacatalog.entryGroups.*</code></p>
<ul>
<li><code>datacatalog.entryGroups.create</code></li>
<li><code>datacatalog.entryGroups.delete</code></li>
<li><code>datacatalog.entryGroups.get</code></li>
<li><code>datacatalog. entryGroups. getIamPolicy</code></li>
<li><code>datacatalog.entryGroups.list</code></li>
<li><code>datacatalog. entryGroups. setIamPolicy</code></li>
<li><code>datacatalog.entryGroups.update</code></li>
<li><code>datacatalog. entryGroups. updateTag</code></li>
</ul>
<p><code>datacatalog. migrationConfig. get</code></p>
<p><code>dataplex.aspectTypes.get</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex.aspectTypes.use</code></p>
<p><code>dataplex.changeRequests.get</code></p>
<p><code>dataplex.changeRequests.list</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.entries.*</code></p>
<ul>
<li><code>dataplex.entries.create</code></li>
<li><code>dataplex.entries.delete</code></li>
<li><code>dataplex.entries.get</code></li>
<li><code>dataplex.entries.getData</code></li>
<li><code>dataplex.entries.link</code></li>
<li><code>dataplex.entries.list</code></li>
<li><code>dataplex.entries.update</code></li>
</ul>
<p><code>dataplex.entryGroups.*</code></p>
<ul>
<li><code>dataplex.entryGroups.create</code></li>
<li><code>dataplex. entryGroups. createTagBinding</code></li>
<li><code>dataplex.entryGroups.delete</code></li>
<li><code>dataplex. entryGroups. deleteTagBinding</code></li>
<li><code>dataplex.entryGroups.export</code></li>
<li><code>dataplex.entryGroups.get</code></li>
<li><code>dataplex. entryGroups. getIamPolicy</code></li>
<li><code>dataplex.entryGroups.import</code></li>
<li><code>dataplex.entryGroups.list</code></li>
<li><code>dataplex. entryGroups. listEffectiveTags</code></li>
<li><code>dataplex. entryGroups. listTagBindings</code></li>
<li><code>dataplex. entryGroups. requestChanges</code></li>
<li><code>dataplex. entryGroups. setIamPolicy</code></li>
<li><code>dataplex.entryGroups.update</code></li>
<li><code>dataplex. entryGroups. useContactsAspect</code></li>
<li><code>dataplex. entryGroups. useContextAspect</code></li>
<li><code>dataplex. entryGroups. useContextEntry</code></li>
<li><code>dataplex. entryGroups. useContextEntryLink</code></li>
<li><code>dataplex. entryGroups. useDataProfileAspect</code></li>
<li><code>dataplex. entryGroups. useDataQualityRuleTemplateAspect</code></li>
<li><code>dataplex. entryGroups. useDataQualityRuleTemplateEntry</code></li>
<li><code>dataplex. entryGroups. useDataQualityScorecardAspect</code></li>
<li><code>dataplex. entryGroups. useDataRulesAspect</code></li>
<li><code>dataplex. entryGroups. useDatabaseDataPolicyAspect</code></li>
<li><code>dataplex. entryGroups. useDefinitionEntryLink</code></li>
<li><code>dataplex. entryGroups. useDescriptionsAspect</code></li>
<li><code>dataplex. entryGroups. useGenericAspect</code></li>
<li><code>dataplex. entryGroups. useGenericEntry</code></li>
<li><code>dataplex. entryGroups. useGraphProfileAspect</code></li>
<li><code>dataplex. entryGroups. useManagedConnectorTypes</code></li>
<li><code>dataplex. entryGroups. useMySQLConnectorTypes</code></li>
<li><code>dataplex. entryGroups. useOracleConnectorTypes</code></li>
<li><code>dataplex. entryGroups. useOverviewAspect</code></li>
<li><code>dataplex. entryGroups. usePostgreSQLConnectorTypes</code></li>
<li><code>dataplex. entryGroups. useQueriesAspect</code></li>
<li><code>dataplex. entryGroups. useRefreshCadenceAspect</code></li>
<li><code>dataplex. entryGroups. useRelatedEntryLink</code></li>
<li><code>dataplex. entryGroups. useSQLAccessAspect</code></li>
<li><code>dataplex. entryGroups. useSQLServerConnectorTypes</code></li>
<li><code>dataplex. entryGroups. useSQLTriggersAspect</code></li>
<li><code>dataplex. entryGroups. useSchemaAspect</code></li>
<li><code>dataplex. entryGroups. useSchemaJoinAspect</code></li>
<li><code>dataplex. entryGroups. useSchemaJoinEntryLink</code></li>
<li><code>dataplex. entryGroups. useSecondaryIndexesAspect</code></li>
<li><code>dataplex. entryGroups. useStorageAspect</code></li>
<li><code>dataplex. entryGroups. useSynonymEntryLink</code></li>
</ul>
<p><code>dataplex.entryLinkTypes.get</code></p>
<p><code>dataplex.entryLinkTypes.list</code></p>
<p><code>dataplex.entryLinkTypes.use</code></p>
<p><code>dataplex.entryLinks.*</code></p>
<ul>
<li><code>dataplex.entryLinks.create</code></li>
<li><code>dataplex.entryLinks.delete</code></li>
<li><code>dataplex.entryLinks.get</code></li>
<li><code>dataplex.entryLinks.reference</code></li>
<li><code>dataplex.entryLinks.update</code></li>
</ul>
<p><code>dataplex.entryTypes.get</code></p>
<p><code>dataplex.entryTypes.list</code></p>
<p><code>dataplex.entryTypes.use</code></p>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>DataCatalog Entry Owner
<p>( <code>roles/ datacatalog.entryOwner</code> )</p>
<p>Full access to entries</p></td>
<td><p><code>datacatalog.entries.*</code></p>
<ul>
<li><code>datacatalog.entries.create</code></li>
<li><code>datacatalog. entries. createGlossary</code></li>
<li><code>datacatalog. entries. createGlossaryCategory</code></li>
<li><code>datacatalog. entries. createGlossaryTerm</code></li>
<li><code>datacatalog.entries.delete</code></li>
<li><code>datacatalog. entries. deleteGlossary</code></li>
<li><code>datacatalog. entries. deleteGlossaryCategory</code></li>
<li><code>datacatalog. entries. deleteGlossaryTerm</code></li>
<li><code>datacatalog.entries.get</code></li>
<li><code>datacatalog. entries. getIamPolicy</code></li>
<li><code>datacatalog.entries.list</code></li>
<li><code>datacatalog. entries. setIamPolicy</code></li>
<li><code>datacatalog.entries.update</code></li>
<li><code>datacatalog. entries. updateContacts</code></li>
<li><code>datacatalog. entries. updateGlossary</code></li>
<li><code>datacatalog. entries. updateGlossaryCategory</code></li>
<li><code>datacatalog. entries. updateGlossaryTerm</code></li>
<li><code>datacatalog. entries. updateOverview</code></li>
<li><code>datacatalog.entries.updateTag</code></li>
</ul>
<p><code>datacatalog.entryGroups.get</code></p>
<p><code>datacatalog. migrationConfig. get</code></p>
<p><code>dataplex.aspectTypes.get</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex.aspectTypes.use</code></p>
<p><code>dataplex.changeRequests.get</code></p>
<p><code>dataplex.changeRequests.list</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.entries.*</code></p>
<ul>
<li><code>dataplex.entries.create</code></li>
<li><code>dataplex.entries.delete</code></li>
<li><code>dataplex.entries.get</code></li>
<li><code>dataplex.entries.getData</code></li>
<li><code>dataplex.entries.link</code></li>
<li><code>dataplex.entries.list</code></li>
<li><code>dataplex.entries.update</code></li>
</ul>
<p><code>dataplex.entryGroups.get</code></p>
<p><code>dataplex. entryGroups. useContactsAspect</code></p>
<p><code>dataplex. entryGroups. useContextAspect</code></p>
<p><code>dataplex. entryGroups. useContextEntry</code></p>
<p><code>dataplex. entryGroups. useContextEntryLink</code></p>
<p><code>dataplex. entryGroups. useDataProfileAspect</code></p>
<p><code>dataplex. entryGroups. useDataQualityRuleTemplateAspect</code></p>
<p><code>dataplex. entryGroups. useDataQualityRuleTemplateEntry</code></p>
<p><code>dataplex. entryGroups. useDataQualityScorecardAspect</code></p>
<p><code>dataplex. entryGroups. useDataRulesAspect</code></p>
<p><code>dataplex. entryGroups. useDatabaseDataPolicyAspect</code></p>
<p><code>dataplex. entryGroups. useDefinitionEntryLink</code></p>
<p><code>dataplex. entryGroups. useDescriptionsAspect</code></p>
<p><code>dataplex. entryGroups. useGenericAspect</code></p>
<p><code>dataplex. entryGroups. useGenericEntry</code></p>
<p><code>dataplex. entryGroups. useGraphProfileAspect</code></p>
<p><code>dataplex. entryGroups. useManagedConnectorTypes</code></p>
<p><code>dataplex. entryGroups. useMySQLConnectorTypes</code></p>
<p><code>dataplex. entryGroups. useOracleConnectorTypes</code></p>
<p><code>dataplex. entryGroups. useOverviewAspect</code></p>
<p><code>dataplex. entryGroups. usePostgreSQLConnectorTypes</code></p>
<p><code>dataplex. entryGroups. useQueriesAspect</code></p>
<p><code>dataplex. entryGroups. useRefreshCadenceAspect</code></p>
<p><code>dataplex. entryGroups. useRelatedEntryLink</code></p>
<p><code>dataplex. entryGroups. useSQLAccessAspect</code></p>
<p><code>dataplex. entryGroups. useSQLServerConnectorTypes</code></p>
<p><code>dataplex. entryGroups. useSQLTriggersAspect</code></p>
<p><code>dataplex. entryGroups. useSchemaAspect</code></p>
<p><code>dataplex. entryGroups. useSchemaJoinAspect</code></p>
<p><code>dataplex. entryGroups. useSchemaJoinEntryLink</code></p>
<p><code>dataplex. entryGroups. useSecondaryIndexesAspect</code></p>
<p><code>dataplex. entryGroups. useStorageAspect</code></p>
<p><code>dataplex. entryGroups. useSynonymEntryLink</code></p>
<p><code>dataplex.entryLinkTypes.get</code></p>
<p><code>dataplex.entryLinkTypes.list</code></p>
<p><code>dataplex.entryLinkTypes.use</code></p>
<p><code>dataplex.entryLinks.*</code></p>
<ul>
<li><code>dataplex.entryLinks.create</code></li>
<li><code>dataplex.entryLinks.delete</code></li>
<li><code>dataplex.entryLinks.get</code></li>
<li><code>dataplex.entryLinks.reference</code></li>
<li><code>dataplex.entryLinks.update</code></li>
</ul>
<p><code>dataplex.entryTypes.get</code></p>
<p><code>dataplex.entryTypes.list</code></p>
<p><code>dataplex.entryTypes.use</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>DataCatalog Entry Viewer
<p>( <code>roles/ datacatalog.entryViewer</code> )</p>
<p>Read access to entries</p></td>
<td><p><code>datacatalog.entries.get</code></p>
<p><code>datacatalog.entries.list</code></p>
<p><code>datacatalog.entryGroups.get</code></p>
<p><code>datacatalog. migrationConfig. get</code></p>
<p><code>datacatalog.relationships.list</code></p>
<p><code>dataplex.entries.get</code></p>
<p><code>dataplex.entries.list</code></p>
<p><code>dataplex.entryGroups.get</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>DataCatalog Glossary Owner <sup>Beta</sup>
<p>( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p>Full access to glossaries</p></td>
<td><p><code>datacatalog.entries.*</code></p>
<ul>
<li><code>datacatalog.entries.create</code></li>
<li><code>datacatalog. entries. createGlossary</code></li>
<li><code>datacatalog. entries. createGlossaryCategory</code></li>
<li><code>datacatalog. entries. createGlossaryTerm</code></li>
<li><code>datacatalog.entries.delete</code></li>
<li><code>datacatalog. entries. deleteGlossary</code></li>
<li><code>datacatalog. entries. deleteGlossaryCategory</code></li>
<li><code>datacatalog. entries. deleteGlossaryTerm</code></li>
<li><code>datacatalog.entries.get</code></li>
<li><code>datacatalog. entries. getIamPolicy</code></li>
<li><code>datacatalog.entries.list</code></li>
<li><code>datacatalog. entries. setIamPolicy</code></li>
<li><code>datacatalog.entries.update</code></li>
<li><code>datacatalog. entries. updateContacts</code></li>
<li><code>datacatalog. entries. updateGlossary</code></li>
<li><code>datacatalog. entries. updateGlossaryCategory</code></li>
<li><code>datacatalog. entries. updateGlossaryTerm</code></li>
<li><code>datacatalog. entries. updateOverview</code></li>
<li><code>datacatalog.entries.updateTag</code></li>
</ul>
<p><code>datacatalog.relationships.*</code></p>
<ul>
<li><code>datacatalog. relationships. create</code></li>
<li><code>datacatalog. relationships. createBelongsTo</code></li>
<li><code>datacatalog. relationships. createIsDescribedBy</code></li>
<li><code>datacatalog. relationships. createIsRelatedTo</code></li>
<li><code>datacatalog. relationships. createIsSynonymousTo</code></li>
<li><code>datacatalog. relationships. delete</code></li>
<li><code>datacatalog. relationships. deleteBelongsTo</code></li>
<li><code>datacatalog. relationships. deleteIsDescribedBy</code></li>
<li><code>datacatalog. relationships. deleteIsRelatedTo</code></li>
<li><code>datacatalog. relationships. deleteIsSynonymousTo</code></li>
<li><code>datacatalog.relationships.list</code></li>
</ul>
<p><code>dataplex.projects.search</code></p></td>
</tr>
<tr class="even">
<td>DataCatalog Glossary User <sup>Beta</sup>
<p>( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p>Can view glossaries and associate terms to entries</p></td>
<td><p><code>datacatalog.entries.get</code></p>
<p><code>datacatalog.entries.list</code></p>
<p><code>datacatalog.relationships.*</code></p>
<ul>
<li><code>datacatalog. relationships. create</code></li>
<li><code>datacatalog. relationships. createBelongsTo</code></li>
<li><code>datacatalog. relationships. createIsDescribedBy</code></li>
<li><code>datacatalog. relationships. createIsRelatedTo</code></li>
<li><code>datacatalog. relationships. createIsSynonymousTo</code></li>
<li><code>datacatalog. relationships. delete</code></li>
<li><code>datacatalog. relationships. deleteBelongsTo</code></li>
<li><code>datacatalog. relationships. deleteIsDescribedBy</code></li>
<li><code>datacatalog. relationships. deleteIsRelatedTo</code></li>
<li><code>datacatalog. relationships. deleteIsSynonymousTo</code></li>
<li><code>datacatalog.relationships.list</code></li>
</ul>
<p><code>dataplex.projects.search</code></p></td>
</tr>
<tr class="odd">
<td>DataCatalog Migration Config Admin
<p>( <code>roles/ datacatalog.migrationConfigAdmin</code> )</p>
<p>Full access to Migration Config</p></td>
<td><p><code>datacatalog.migrationConfig.*</code></p>
<ul>
<li><code>datacatalog. migrationConfig. get</code></li>
<li><code>datacatalog. migrationConfig. set</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>DataCatalog Search Admin
<p>( <code>roles/ datacatalog.searchAdmin</code> )</p>
<p>Can search all metadata for a project/org in DataCatalog</p></td>
<td><p><code>datacatalog.catalogs.searchAll</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Data Catalog Tag Editor
<p>( <code>roles/ datacatalog.tagEditor</code> )</p>
<p>Access to modify metadata tags for entries, as well as BigQuery and Pub/Sub data assets</p></td>
<td><p><code>bigquery.connections.updateTag</code></p>
<p><code>bigquery.datasets.updateTag</code></p>
<p><code>bigquery.models.updateTag</code></p>
<p><code>bigquery.routines.updateTag</code></p>
<p><code>bigquery.tables.updateTag</code></p>
<p><code>datacatalog.entries.updateTag</code></p>
<p><code>datacatalog. entryGroups. updateTag</code></p>
<p><code>dataplex.entries.update</code></p>
<p><code>pubsub.topics.updateTag</code></p></td>
</tr>
<tr class="even">
<td>Data Catalog TagTemplate Creator
<p>( <code>roles/ datacatalog.tagTemplateCreator</code> )</p>
<p>Access to create new tag templates</p></td>
<td><p><code>datacatalog. tagTemplates. create</code></p>
<p><code>datacatalog.tagTemplates.get</code></p>
<p><code>dataplex.aspectTypes.create</code></p>
<p><code>dataplex.aspectTypes.get</code></p>
<p><code>dataplex.projects.search</code></p></td>
</tr>
<tr class="odd">
<td>Data Catalog TagTemplate Owner
<p>( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p>Full access to tag templates</p></td>
<td><p><code>datacatalog. migrationConfig. get</code></p>
<p><code>datacatalog.tagTemplates.*</code></p>
<ul>
<li><code>datacatalog. tagTemplates. create</code></li>
<li><code>datacatalog. tagTemplates. delete</code></li>
<li><code>datacatalog.tagTemplates.get</code></li>
<li><code>datacatalog. tagTemplates. getIamPolicy</code></li>
<li><code>datacatalog. tagTemplates. getTag</code></li>
<li><code>datacatalog. tagTemplates. setIamPolicy</code></li>
<li><code>datacatalog. tagTemplates. update</code></li>
<li><code>datacatalog.tagTemplates.use</code></li>
</ul>
<p><code>dataplex.aspectTypes.*</code></p>
<ul>
<li><code>dataplex.aspectTypes.create</code></li>
<li><code>dataplex.aspectTypes.delete</code></li>
<li><code>dataplex.aspectTypes.get</code></li>
<li><code>dataplex. aspectTypes. getIamPolicy</code></li>
<li><code>dataplex.aspectTypes.list</code></li>
<li><code>dataplex. aspectTypes. setIamPolicy</code></li>
<li><code>dataplex.aspectTypes.update</code></li>
<li><code>dataplex.aspectTypes.use</code></li>
</ul>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Data Catalog TagTemplate User
<p>( <code>roles/ datacatalog.tagTemplateUser</code> )</p>
<p>Access to apply a tag template to an entry (to modify tags, see Data Catalog Tag Editor)</p></td>
<td><p><code>datacatalog. migrationConfig. get</code></p>
<p><code>datacatalog.tagTemplates.get</code></p>
<p><code>datacatalog. tagTemplates. getTag</code></p>
<p><code>datacatalog.tagTemplates.use</code></p>
<p><code>dataplex.aspectTypes.get</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex.aspectTypes.use</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Data Catalog TagTemplate Viewer
<p>( <code>roles/ datacatalog.tagTemplateViewer</code> )</p>
<p>Read access to templates and tags created using the templates</p></td>
<td><p><code>datacatalog.tagTemplates.get</code></p>
<p><code>datacatalog. tagTemplates. getTag</code></p>
<p><code>dataplex.aspectTypes.get</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Data Catalog permissions

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
<td><code>datacatalog.catalogs.searchAll</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.searchAdmin">DataCatalog Search Admin</a> ( <code>roles/ datacatalog.searchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>datacatalog. categories. fineGrainedGet</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryFineGrainedReader">Fine-Grained Reader</a> ( <code>roles/ datacatalog.categoryFineGrainedReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>datacatalog. categories. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code>roles/ datacatalog.categoryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>datacatalog. categories. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code>roles/ datacatalog.categoryAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>datacatalog.entries.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. entries. createGlossary</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog. entries. createGlossaryCategory</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. entries. createGlossaryTerm</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog.entries.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. entries. deleteGlossary</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog. entries. deleteGlossaryCategory</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. entries. deleteGlossaryTerm</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog.entries.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code>roles/ datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code>roles/ datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>datacatalog. entries. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog.entries.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code>roles/ datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code>roles/ datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. entries. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog.entries.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. entries. updateContacts</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code>roles/ datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog. entries. updateGlossary</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. entries. updateGlossaryCategory</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog. entries. updateGlossaryTerm</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. entries. updateOverview</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code>roles/ datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog.entries.updateTag</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagEditor">Data Catalog Tag Editor</a> ( <code>roles/ datacatalog.tagEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog.entryGroups.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code>roles/ datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog.entryGroups.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog.entryGroups.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code>roles/ datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code>roles/ datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code>roles/ datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog. entryGroups. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog.entryGroups.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code>roles/ datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog. entryGroups. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog.entryGroups.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog. entryGroups. updateTag</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagEditor">Data Catalog Tag Editor</a> ( <code>roles/ datacatalog.tagEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. migrationConfig. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code>roles/ datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code>roles/ datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.migrationConfigAdmin">DataCatalog Migration Config Admin</a> ( <code>roles/ datacatalog.migrationConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code>roles/ datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code>roles/ dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code>roles/ dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>datacatalog. migrationConfig. set</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.migrationConfigAdmin">DataCatalog Migration Config Admin</a> ( <code>roles/ datacatalog.migrationConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog. relationships. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. relationships. createBelongsTo</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog. relationships. createIsDescribedBy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. relationships. createIsRelatedTo</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog. relationships. createIsSynonymousTo</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. relationships. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog. relationships. deleteBelongsTo</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. relationships. deleteIsDescribedBy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog. relationships. deleteIsRelatedTo</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. relationships. deleteIsSynonymousTo</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datacatalog.relationships.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code>roles/ datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code>roles/ datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog. tagTemplates. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateCreator">Data Catalog TagTemplate Creator</a> ( <code>roles/ datacatalog.tagTemplateCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>datacatalog. tagTemplates. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>datacatalog.tagTemplates.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateCreator">Data Catalog TagTemplate Creator</a> ( <code>roles/ datacatalog.tagTemplateCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code>roles/ datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code>roles/ datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>datacatalog. tagTemplates. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>datacatalog. tagTemplates. getTag</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code>roles/ datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code>roles/ datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>datacatalog. tagTemplates. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>datacatalog. tagTemplates. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>datacatalog.tagTemplates.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code>roles/ datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>datacatalog.taxonomies.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code>roles/ datacatalog.categoryAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>datacatalog.taxonomies.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code>roles/ datacatalog.categoryAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>datacatalog.taxonomies.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code>roles/ datacatalog.categoryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>datacatalog. taxonomies. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code>roles/ datacatalog.categoryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog.taxonomies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code>roles/ datacatalog.categoryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>datacatalog. taxonomies. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code>roles/ datacatalog.categoryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>datacatalog.taxonomies.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code>roles/ datacatalog.categoryAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
