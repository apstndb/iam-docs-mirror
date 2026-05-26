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
<td><h4 id="datacatalog.admin" class="role-title add-link" data-text="Data Catalog Admin" tabindex="-1">Data Catalog Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p>Full access to all DataCatalog resources</p></td>
<td><p><code dir="ltr" translate="no">bigquery.connections.get</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.models.getMetadata</code></p>
<p><code dir="ltr" translate="no">bigquery.models.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.get</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.catalogs.searchAll</code></p>
<p><code dir="ltr" translate="no">datacatalog.  categories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.  categories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.entries.create</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  createGlossary</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  createGlossaryCategory</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  createGlossaryTerm</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossary</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossaryCategory</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossaryTerm</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.list</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.update</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateContacts</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossary</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossaryCategory</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossaryTerm</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateOverview</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.entryGroups.create</code></li>
<li><code dir="ltr" translate="no">datacatalog.entryGroups.delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.entryGroups.get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entryGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.entryGroups.list</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entryGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.entryGroups.update</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entryGroups.  updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">datacatalog.migrationConfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  migrationConfig.  set</code></li>
</ul>
<p><code dir="ltr" translate="no">datacatalog.operations.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.relationships.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  create</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createBelongsTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createIsDescribedBy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createIsRelatedTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createIsSynonymousTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteBelongsTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsDescribedBy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsRelatedTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsSynonymousTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.relationships.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  create</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.tagTemplates.get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getTag</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  update</code></li>
<li><code dir="ltr" translate="no">datacatalog.tagTemplates.use</code></li>
</ul>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.taxonomies.create</code></li>
<li><code dir="ltr" translate="no">datacatalog.taxonomies.delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.taxonomies.get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  taxonomies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.taxonomies.list</code></li>
<li><code dir="ltr" translate="no">datacatalog.  taxonomies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.taxonomies.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.create</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  aspectTypes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  aspectTypes.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.update</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.use</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.entries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.entries.create</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.get</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.getData</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.link</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.list</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.entryGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.entryGroups.create</code></li>
<li><code dir="ltr" translate="no">dataplex.entryGroups.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.entryGroups.export</code></li>
<li><code dir="ltr" translate="no">dataplex.entryGroups.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.entryGroups.import</code></li>
<li><code dir="ltr" translate="no">dataplex.entryGroups.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.entryGroups.update</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useContactsAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataProfileAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataQualityRuleTemplateAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataQualityRuleTemplateEntry</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataQualityScorecardAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataRulesAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDatabaseDataPolicyAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDefinitionEntryLink</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDescriptionsAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useGenericAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useGenericEntry</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useGraphProfileAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useMySQLConnectorTypes</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useOracleConnectorTypes</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useOverviewAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  usePostgreSQLConnectorTypes</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useQueriesAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useRefreshCadenceAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useRelatedEntryLink</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLAccessAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLServerConnectorTypes</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLTriggersAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaJoinAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaJoinEntryLink</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSecondaryIndexesAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useStorageAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSynonymEntryLink</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.entryLinks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.entryLinks.create</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.get</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.reference</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.entryTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.entryTypes.create</code></li>
<li><code dir="ltr" translate="no">dataplex.entryTypes.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.entryTypes.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryTypes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.entryTypes.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryTypes.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.entryTypes.update</code></li>
<li><code dir="ltr" translate="no">dataplex.entryTypes.use</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.glossaries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.glossaries.create</code></li>
<li><code dir="ltr" translate="no">dataplex.glossaries.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.glossaries.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  glossaries.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.glossaries.import</code></li>
<li><code dir="ltr" translate="no">dataplex.glossaries.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  glossaries.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.glossaries.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.glossaryCategories.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.  glossaryCategories.  create</code></li>
<li><code dir="ltr" translate="no">dataplex.  glossaryCategories.  delete</code></li>
<li><code dir="ltr" translate="no">dataplex.  glossaryCategories.  get</code></li>
<li><code dir="ltr" translate="no">dataplex.  glossaryCategories.  list</code></li>
<li><code dir="ltr" translate="no">dataplex.  glossaryCategories.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.glossaryTerms.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.glossaryTerms.create</code></li>
<li><code dir="ltr" translate="no">dataplex.glossaryTerms.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.glossaryTerms.get</code></li>
<li><code dir="ltr" translate="no">dataplex.glossaryTerms.list</code></li>
<li><code dir="ltr" translate="no">dataplex.glossaryTerms.update</code></li>
<li><code dir="ltr" translate="no">dataplex.glossaryTerms.use</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.updateTag</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.editor" class="role-title add-link" data-text="Data Catalog Editor" tabindex="-1">Data Catalog Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p>Editor role for Data Catalog</p></td>
<td><p><code dir="ltr" translate="no">bigquery.connections.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.models.getMetadata</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.catalogs.searchAll</code></p>
<p><code dir="ltr" translate="no">datacatalog.  categories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.create</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  createGlossary</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  createGlossaryCategory</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  createGlossaryTerm</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.delete</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossary</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossaryCategory</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossaryTerm</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.update</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  updateContacts</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossary</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossaryCategory</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossaryTerm</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  updateOverview</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.updateTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.create</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.delete</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entryGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.update</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entryGroups.  updateTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.migrationConfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  migrationConfig.  set</code></li>
</ul>
<p><code dir="ltr" translate="no">datacatalog.operations.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.relationships.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  create</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createBelongsTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createIsDescribedBy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createIsRelatedTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createIsSynonymousTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteBelongsTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsDescribedBy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsRelatedTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsSynonymousTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.relationships.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  create</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  delete</code></p>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  update</code></p>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.use</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  taxonomies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.list</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  aspectTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entryLinks.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaries.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  glossaries.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaries.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  glossaryCategories.  get</code></p>
<p><code dir="ltr" translate="no">dataplex.  glossaryCategories.  list</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaryTerms.get</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaryTerms.list</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.viewer" class="role-title add-link" data-text="Data Catalog Viewer" tabindex="-1">Data Catalog Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p>Provides metadata read access to catalogued Google Cloud assets for BigQuery and Pub/Sub</p></td>
<td><p><code dir="ltr" translate="no">bigquery.connections.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.models.getMetadata</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">datacatalog.operations.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.relationships.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.list</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  aspectTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entryLinks.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaries.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  glossaries.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaries.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  glossaryCategories.  get</code></p>
<p><code dir="ltr" translate="no">dataplex.  glossaryCategories.  list</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaryTerms.get</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaryTerms.list</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.categoryAdmin" class="role-title add-link" data-text="Policy Tag Admin" tabindex="-1">Policy Tag Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.categoryAdmin</code> )</p>
<p>Manage taxonomies</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  categories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.  categories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.taxonomies.create</code></li>
<li><code dir="ltr" translate="no">datacatalog.taxonomies.delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.taxonomies.get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  taxonomies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.taxonomies.list</code></li>
<li><code dir="ltr" translate="no">datacatalog.  taxonomies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.taxonomies.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.categoryFineGrainedReader" class="role-title add-link" data-text="Fine-Grained Reader" tabindex="-1">Fine-Grained Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.categoryFineGrainedReader</code> )</p>
<p>Read access to sub-resources tagged by a policy tag, for example, BigQuery columns</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  categories.  fineGrainedGet</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.dataSteward" class="role-title add-link" data-text="DataCatalog Data Steward Beta" tabindex="-1">DataCatalog Data Steward <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p>Can update overview and data steward fields</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.entries.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  updateContacts</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  updateOverview</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">datacatalog.relationships.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useContactsAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useOverviewAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entryGroupCreator" class="role-title add-link" data-text="DataCatalog EntryGroup Creator" tabindex="-1">DataCatalog EntryGroup Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.entryGroupCreator</code> )</p>
<p>Can create new entryGroups</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.entryGroups.create</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.create</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entryGroupOwner" class="role-title add-link" data-text="DataCatalog EntryGroup Owner" tabindex="-1">DataCatalog EntryGroup Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p>Full access to entryGroups</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.entries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.entries.create</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  createGlossary</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  createGlossaryCategory</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  createGlossaryTerm</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossary</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossaryCategory</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossaryTerm</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.list</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.update</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateContacts</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossary</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossaryCategory</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossaryTerm</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateOverview</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.entryGroups.create</code></li>
<li><code dir="ltr" translate="no">datacatalog.entryGroups.delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.entryGroups.get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entryGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.entryGroups.list</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entryGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.entryGroups.update</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entryGroups.  updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.use</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.entries.create</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.get</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.getData</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.link</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.list</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.entryGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.entryGroups.create</code></li>
<li><code dir="ltr" translate="no">dataplex.entryGroups.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.entryGroups.export</code></li>
<li><code dir="ltr" translate="no">dataplex.entryGroups.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.entryGroups.import</code></li>
<li><code dir="ltr" translate="no">dataplex.entryGroups.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.entryGroups.update</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useContactsAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataProfileAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataQualityRuleTemplateAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataQualityRuleTemplateEntry</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataQualityScorecardAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataRulesAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDatabaseDataPolicyAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDefinitionEntryLink</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useDescriptionsAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useGenericAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useGenericEntry</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useGraphProfileAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useMySQLConnectorTypes</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useOracleConnectorTypes</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useOverviewAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  usePostgreSQLConnectorTypes</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useQueriesAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useRefreshCadenceAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useRelatedEntryLink</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLAccessAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLServerConnectorTypes</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLTriggersAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaJoinAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaJoinEntryLink</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSecondaryIndexesAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useStorageAspect</code></li>
<li><code dir="ltr" translate="no">dataplex.  entryGroups.  useSynonymEntryLink</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.entryLinks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.entryLinks.create</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.get</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.reference</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.entryTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.use</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entryOwner" class="role-title add-link" data-text="DataCatalog Entry Owner" tabindex="-1">DataCatalog Entry Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p>Full access to entries</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.entries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.entries.create</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  createGlossary</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  createGlossaryCategory</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  createGlossaryTerm</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossary</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossaryCategory</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossaryTerm</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.list</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.update</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateContacts</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossary</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossaryCategory</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossaryTerm</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateOverview</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.use</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.entries.create</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.get</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.getData</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.link</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.list</code></li>
<li><code dir="ltr" translate="no">dataplex.entries.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useContactsAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataProfileAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataQualityRuleTemplateAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataQualityRuleTemplateEntry</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataQualityScorecardAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataRulesAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useDatabaseDataPolicyAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useDefinitionEntryLink</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useDescriptionsAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useGenericAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useGenericEntry</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useGraphProfileAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useMySQLConnectorTypes</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useOracleConnectorTypes</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useOverviewAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  usePostgreSQLConnectorTypes</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useQueriesAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useRefreshCadenceAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useRelatedEntryLink</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLAccessAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLServerConnectorTypes</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLTriggersAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaJoinAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaJoinEntryLink</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSecondaryIndexesAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useStorageAspect</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSynonymEntryLink</code></p>
<p><code dir="ltr" translate="no">dataplex.entryLinks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.entryLinks.create</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.get</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.reference</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.entryTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.use</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entryViewer" class="role-title add-link" data-text="DataCatalog Entry Viewer" tabindex="-1">DataCatalog Entry Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.entryViewer</code> )</p>
<p>Read access to entries</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.entries.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">datacatalog.relationships.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.glossaryOwner" class="role-title add-link" data-text="DataCatalog Glossary Owner Beta" tabindex="-1">DataCatalog Glossary Owner <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p>Full access to glossaries</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.entries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.entries.create</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  createGlossary</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  createGlossaryCategory</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  createGlossaryTerm</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossary</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossaryCategory</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossaryTerm</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.list</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.update</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateContacts</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossary</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossaryCategory</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossaryTerm</code></li>
<li><code dir="ltr" translate="no">datacatalog.  entries.  updateOverview</code></li>
<li><code dir="ltr" translate="no">datacatalog.entries.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">datacatalog.relationships.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  create</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createBelongsTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createIsDescribedBy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createIsRelatedTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createIsSynonymousTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteBelongsTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsDescribedBy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsRelatedTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsSynonymousTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.relationships.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.glossaryUser" class="role-title add-link" data-text="DataCatalog Glossary User Beta" tabindex="-1">DataCatalog Glossary User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p>
<p>Can view glossaries and associate terms to entries</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.entries.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.relationships.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  create</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createBelongsTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createIsDescribedBy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createIsRelatedTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  createIsSynonymousTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteBelongsTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsDescribedBy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsRelatedTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsSynonymousTo</code></li>
<li><code dir="ltr" translate="no">datacatalog.relationships.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.migrationConfigAdmin" class="role-title add-link" data-text="DataCatalog Migration Config Admin" tabindex="-1">DataCatalog Migration Config Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.migrationConfigAdmin</code> )</p>
<p>Full access to Migration Config</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.migrationConfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  migrationConfig.  set</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.searchAdmin" class="role-title add-link" data-text="DataCatalog Search Admin" tabindex="-1">DataCatalog Search Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.searchAdmin</code> )</p>
<p>Can search all metadata for a project/org in DataCatalog</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.catalogs.searchAll</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.tagEditor" class="role-title add-link" data-text="Data Catalog Tag Editor" tabindex="-1">Data Catalog Tag Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.tagEditor</code> )</p>
<p>Access to modify metadata tags for entries, as well as BigQuery and Pub/Sub data assets</p></td>
<td><p><code dir="ltr" translate="no">bigquery.connections.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.models.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.updateTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entryGroups.  updateTag</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.update</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.updateTag</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.tagTemplateCreator" class="role-title add-link" data-text="Data Catalog TagTemplate Creator" tabindex="-1">Data Catalog TagTemplate Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.tagTemplateCreator</code> )</p>
<p>Access to create new tag templates</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  create</code></p>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.get</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.create</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.tagTemplateOwner" class="role-title add-link" data-text="Data Catalog TagTemplate Owner" tabindex="-1">Data Catalog TagTemplate Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p>Full access to tag templates</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  create</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.tagTemplates.get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getTag</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  update</code></li>
<li><code dir="ltr" translate="no">datacatalog.tagTemplates.use</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.create</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  aspectTypes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  aspectTypes.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.update</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.use</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.tagTemplateUser" class="role-title add-link" data-text="Data Catalog TagTemplate User" tabindex="-1">Data Catalog TagTemplate User</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.tagTemplateUser</code> )</p>
<p>Access to apply a tag template to an entry (to modify tags, see Data Catalog Tag Editor)</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.use</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.use</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.tagTemplateViewer" class="role-title add-link" data-text="Data Catalog TagTemplate Viewer" tabindex="-1">Data Catalog TagTemplate Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  datacatalog.tagTemplateViewer</code> )</p>
<p>Read access to templates and tags created using the templates</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.tagTemplates.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getTag</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="datacatalog.catalogs.searchAll" class="permission-name add-link" data-text="datacatalog.catalogs.searchAll" tabindex="-1"><code dir="ltr" translate="no">datacatalog.catalogs.searchAll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.searchAdmin">DataCatalog Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.searchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.categories.fineGrainedGet" class="permission-name add-link" data-text="datacatalog.categories.fineGrainedGet" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  categories.  fineGrainedGet</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryFineGrainedReader">Fine-Grained Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.categoryFineGrainedReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.categories.getIamPolicy" class="permission-name add-link" data-text="datacatalog.categories.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  categories.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.categoryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.categories.setIamPolicy" class="permission-name add-link" data-text="datacatalog.categories.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  categories.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.categoryAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entries.create" class="permission-name add-link" data-text="datacatalog.entries.create" tabindex="-1"><code dir="ltr" translate="no">datacatalog.entries.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entries.createGlossary" class="permission-name add-link" data-text="datacatalog.entries.createGlossary" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  createGlossary</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entries.createGlossaryCategory" class="permission-name add-link" data-text="datacatalog.entries.createGlossaryCategory" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  createGlossaryCategory</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entries.createGlossaryTerm" class="permission-name add-link" data-text="datacatalog.entries.createGlossaryTerm" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  createGlossaryTerm</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entries.delete" class="permission-name add-link" data-text="datacatalog.entries.delete" tabindex="-1"><code dir="ltr" translate="no">datacatalog.entries.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entries.deleteGlossary" class="permission-name add-link" data-text="datacatalog.entries.deleteGlossary" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossary</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entries.deleteGlossaryCategory" class="permission-name add-link" data-text="datacatalog.entries.deleteGlossaryCategory" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossaryCategory</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entries.deleteGlossaryTerm" class="permission-name add-link" data-text="datacatalog.entries.deleteGlossaryTerm" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  deleteGlossaryTerm</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entries.get" class="permission-name add-link" data-text="datacatalog.entries.get" tabindex="-1"><code dir="ltr" translate="no">datacatalog.entries.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entries.getIamPolicy" class="permission-name add-link" data-text="datacatalog.entries.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entries.list" class="permission-name add-link" data-text="datacatalog.entries.list" tabindex="-1"><code dir="ltr" translate="no">datacatalog.entries.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entries.setIamPolicy" class="permission-name add-link" data-text="datacatalog.entries.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entries.update" class="permission-name add-link" data-text="datacatalog.entries.update" tabindex="-1"><code dir="ltr" translate="no">datacatalog.entries.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entries.updateContacts" class="permission-name add-link" data-text="datacatalog.entries.updateContacts" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  updateContacts</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entries.updateGlossary" class="permission-name add-link" data-text="datacatalog.entries.updateGlossary" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossary</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entries.updateGlossaryCategory" class="permission-name add-link" data-text="datacatalog.entries.updateGlossaryCategory" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossaryCategory</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entries.updateGlossaryTerm" class="permission-name add-link" data-text="datacatalog.entries.updateGlossaryTerm" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  updateGlossaryTerm</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entries.updateOverview" class="permission-name add-link" data-text="datacatalog.entries.updateOverview" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entries.  updateOverview</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entries.updateTag" class="permission-name add-link" data-text="datacatalog.entries.updateTag" tabindex="-1"><code dir="ltr" translate="no">datacatalog.entries.updateTag</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagEditor">Data Catalog Tag Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entryGroups.create" class="permission-name add-link" data-text="datacatalog.entryGroups.create" tabindex="-1"><code dir="ltr" translate="no">datacatalog.entryGroups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entryGroups.delete" class="permission-name add-link" data-text="datacatalog.entryGroups.delete" tabindex="-1"><code dir="ltr" translate="no">datacatalog.entryGroups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entryGroups.get" class="permission-name add-link" data-text="datacatalog.entryGroups.get" tabindex="-1"><code dir="ltr" translate="no">datacatalog.entryGroups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entryGroups.getIamPolicy" class="permission-name add-link" data-text="datacatalog.entryGroups.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entryGroups.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entryGroups.list" class="permission-name add-link" data-text="datacatalog.entryGroups.list" tabindex="-1"><code dir="ltr" translate="no">datacatalog.entryGroups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entryGroups.setIamPolicy" class="permission-name add-link" data-text="datacatalog.entryGroups.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entryGroups.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.entryGroups.update" class="permission-name add-link" data-text="datacatalog.entryGroups.update" tabindex="-1"><code dir="ltr" translate="no">datacatalog.entryGroups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.entryGroups.updateTag" class="permission-name add-link" data-text="datacatalog.entryGroups.updateTag" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  entryGroups.  updateTag</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagEditor">Data Catalog Tag Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.migrationConfig.get" class="permission-name add-link" data-text="datacatalog.migrationConfig.get" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.migrationConfigAdmin">DataCatalog Migration Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.migrationConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.migrationConfig.set" class="permission-name add-link" data-text="datacatalog.migrationConfig.set" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  migrationConfig.  set</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.migrationConfigAdmin">DataCatalog Migration Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.migrationConfigAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.operations.list" class="permission-name add-link" data-text="datacatalog.operations.list" tabindex="-1"><code dir="ltr" translate="no">datacatalog.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.relationships.create" class="permission-name add-link" data-text="datacatalog.relationships.create" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  relationships.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.relationships.createBelongsTo" class="permission-name add-link" data-text="datacatalog.relationships.createBelongsTo" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  relationships.  createBelongsTo</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.relationships.createIsDescribedBy" class="permission-name add-link" data-text="datacatalog.relationships.createIsDescribedBy" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  relationships.  createIsDescribedBy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.relationships.createIsRelatedTo" class="permission-name add-link" data-text="datacatalog.relationships.createIsRelatedTo" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  relationships.  createIsRelatedTo</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.relationships.createIsSynonymousTo" class="permission-name add-link" data-text="datacatalog.relationships.createIsSynonymousTo" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  relationships.  createIsSynonymousTo</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.relationships.delete" class="permission-name add-link" data-text="datacatalog.relationships.delete" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  relationships.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.relationships.deleteBelongsTo" class="permission-name add-link" data-text="datacatalog.relationships.deleteBelongsTo" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  relationships.  deleteBelongsTo</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.relationships.deleteIsDescribedBy" class="permission-name add-link" data-text="datacatalog.relationships.deleteIsDescribedBy" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsDescribedBy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.relationships.deleteIsRelatedTo" class="permission-name add-link" data-text="datacatalog.relationships.deleteIsRelatedTo" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsRelatedTo</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.relationships.deleteIsSynonymousTo" class="permission-name add-link" data-text="datacatalog.relationships.deleteIsSynonymousTo" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  relationships.  deleteIsSynonymousTo</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.relationships.list" class="permission-name add-link" data-text="datacatalog.relationships.list" tabindex="-1"><code dir="ltr" translate="no">datacatalog.relationships.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.tagTemplates.create" class="permission-name add-link" data-text="datacatalog.tagTemplates.create" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  tagTemplates.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateCreator">Data Catalog TagTemplate Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.tagTemplates.delete" class="permission-name add-link" data-text="datacatalog.tagTemplates.delete" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  tagTemplates.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.tagTemplates.get" class="permission-name add-link" data-text="datacatalog.tagTemplates.get" tabindex="-1"><code dir="ltr" translate="no">datacatalog.tagTemplates.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateCreator">Data Catalog TagTemplate Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.tagTemplates.getIamPolicy" class="permission-name add-link" data-text="datacatalog.tagTemplates.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.tagTemplates.getTag" class="permission-name add-link" data-text="datacatalog.tagTemplates.getTag" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getTag</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.tagTemplates.setIamPolicy" class="permission-name add-link" data-text="datacatalog.tagTemplates.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  tagTemplates.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.tagTemplates.update" class="permission-name add-link" data-text="datacatalog.tagTemplates.update" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  tagTemplates.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.tagTemplates.use" class="permission-name add-link" data-text="datacatalog.tagTemplates.use" tabindex="-1"><code dir="ltr" translate="no">datacatalog.tagTemplates.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.taxonomies.create" class="permission-name add-link" data-text="datacatalog.taxonomies.create" tabindex="-1"><code dir="ltr" translate="no">datacatalog.taxonomies.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.categoryAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.taxonomies.delete" class="permission-name add-link" data-text="datacatalog.taxonomies.delete" tabindex="-1"><code dir="ltr" translate="no">datacatalog.taxonomies.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.categoryAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.taxonomies.get" class="permission-name add-link" data-text="datacatalog.taxonomies.get" tabindex="-1"><code dir="ltr" translate="no">datacatalog.taxonomies.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.categoryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.taxonomies.getIamPolicy" class="permission-name add-link" data-text="datacatalog.taxonomies.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  taxonomies.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.categoryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.taxonomies.list" class="permission-name add-link" data-text="datacatalog.taxonomies.list" tabindex="-1"><code dir="ltr" translate="no">datacatalog.taxonomies.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.categoryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datacatalog.taxonomies.setIamPolicy" class="permission-name add-link" data-text="datacatalog.taxonomies.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datacatalog.  taxonomies.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.categoryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datacatalog.taxonomies.update" class="permission-name add-link" data-text="datacatalog.taxonomies.update" tabindex="-1"><code dir="ltr" translate="no">datacatalog.taxonomies.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.categoryAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
