---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/dataplex
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex
title: Knowledge Catalog roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Knowledge Catalog. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Knowledge Catalog roles

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
<td><h4 id="dataplex.admin" class="role-title add-link" data-text="Dataplex Administrator" tabindex="-1">Dataplex Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p>Full access to Dataplex Universal Catalog resources, except for catalog resources like entries and entry groups.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  analyzeIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllIamPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">dataplex.assetActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.create</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.get</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.list</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.update</code></p>
<p><code dir="ltr" translate="no">dataplex.content.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.content.create</code></li>
<li><code dir="ltr" translate="no">dataplex.content.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.content.get</code></li>
<li><code dir="ltr" translate="no">dataplex.content.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.content.list</code></li>
<li><code dir="ltr" translate="no">dataplex.content.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.content.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.dataAssets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.dataAssets.create</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.get</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.list</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  create</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  delete</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  get</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  list</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.dataAttributes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.dataAttributes.bind</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAttributes.create</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAttributes.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAttributes.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAttributes.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributes.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAttributes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.dataProducts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.dataProducts.create</code></li>
<li><code dir="ltr" translate="no">dataplex.dataProducts.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.dataProducts.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataProducts.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.dataProducts.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataProducts.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.dataProducts.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  configureDataAccess</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  configureResourceAccess</code></li>
<li><code dir="ltr" translate="no">dataplex.dataTaxonomies.create</code></li>
<li><code dir="ltr" translate="no">dataplex.dataTaxonomies.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.dataTaxonomies.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.dataTaxonomies.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.dataTaxonomies.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.datascans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.datascans.cancel</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.create</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.get</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.getData</code></li>
<li><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.list</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.run</code></li>
<li><code dir="ltr" translate="no">dataplex.  datascans.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.entities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.entities.create</code></li>
<li><code dir="ltr" translate="no">dataplex.entities.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.entities.get</code></li>
<li><code dir="ltr" translate="no">dataplex.entities.list</code></li>
<li><code dir="ltr" translate="no">dataplex.entities.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.entries.link</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.export</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.import</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useDefinitionEntryLink</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useRelatedEntryLink</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaJoinEntryLink</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  useSynonymEntryLink</code></p>
<p><code dir="ltr" translate="no">dataplex.entryLinks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.entryLinks.create</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.get</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.reference</code></li>
<li><code dir="ltr" translate="no">dataplex.entryLinks.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.environments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.environments.create</code></li>
<li><code dir="ltr" translate="no">dataplex.environments.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.environments.execute</code></li>
<li><code dir="ltr" translate="no">dataplex.environments.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  environments.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.environments.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  environments.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.environments.update</code></li>
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
<p><code dir="ltr" translate="no">dataplex.lakeActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.lakes.create</code></li>
<li><code dir="ltr" translate="no">dataplex.lakes.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.lakes.get</code></li>
<li><code dir="ltr" translate="no">dataplex.lakes.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.lakes.list</code></li>
<li><code dir="ltr" translate="no">dataplex.lakes.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.lakes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.locations.get</code></li>
<li><code dir="ltr" translate="no">dataplex.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.metadataFeeds.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.metadataFeeds.create</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataFeeds.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataFeeds.get</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataFeeds.list</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataFeeds.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.metadataJobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.metadataJobs.cancel</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataJobs.create</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataJobs.get</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataJobs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.operations.cancel</code></li>
<li><code dir="ltr" translate="no">dataplex.operations.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.operations.get</code></li>
<li><code dir="ltr" translate="no">dataplex.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.partitions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.partitions.create</code></li>
<li><code dir="ltr" translate="no">dataplex.partitions.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.partitions.get</code></li>
<li><code dir="ltr" translate="no">dataplex.partitions.list</code></li>
<li><code dir="ltr" translate="no">dataplex.partitions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.tasks.cancel</code></li>
<li><code dir="ltr" translate="no">dataplex.tasks.create</code></li>
<li><code dir="ltr" translate="no">dataplex.tasks.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.tasks.get</code></li>
<li><code dir="ltr" translate="no">dataplex.tasks.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.tasks.list</code></li>
<li><code dir="ltr" translate="no">dataplex.tasks.run</code></li>
<li><code dir="ltr" translate="no">dataplex.tasks.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.tasks.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.zoneActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.zones.create</code></li>
<li><code dir="ltr" translate="no">dataplex.zones.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.zones.get</code></li>
<li><code dir="ltr" translate="no">dataplex.zones.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.zones.list</code></li>
<li><code dir="ltr" translate="no">dataplex.zones.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.zones.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataScanAdmin" class="role-title add-link" data-text="Dataplex DataScan Administrator" tabindex="-1">Dataplex DataScan Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p>Full access to DataScan resources.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.datascans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.datascans.cancel</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.create</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.get</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.getData</code></li>
<li><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.list</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.run</code></li>
<li><code dir="ltr" translate="no">dataplex.  datascans.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.editor" class="role-title add-link" data-text="Dataplex Editor" tabindex="-1">Dataplex Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p>Write access to Dataplex Universal Catalog resources, except for catalog resources like entries, entry groups, and glossaries.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  analyzeIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.assetActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.create</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.get</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.list</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.update</code></p>
<p><code dir="ltr" translate="no">dataplex.content.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.content.get</code></p>
<p><code dir="ltr" translate="no">dataplex.content.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.content.list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAssets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.dataAssets.create</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.get</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.list</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  create</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  delete</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  list</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  update</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAttributes.bind</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAttributes.create</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAttributes.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAttributes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAttributes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAttributes.update</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.create</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataProducts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.update</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  configureDataAccess</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  configureResourceAccess</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.create</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.update</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.cancel</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.create</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.list</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.run</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.update</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.create</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  environments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.list</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.update</code></p>
<p><code dir="ltr" translate="no">dataplex.lakeActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.create</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.update</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.operations.cancel</code></li>
<li><code dir="ltr" translate="no">dataplex.operations.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.operations.get</code></li>
<li><code dir="ltr" translate="no">dataplex.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.tasks.cancel</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.create</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.get</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.list</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.run</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.update</code></p>
<p><code dir="ltr" translate="no">dataplex.zoneActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.create</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.get</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.list</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.viewer" class="role-title add-link" data-text="Dataplex Viewer" tabindex="-1">Dataplex Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p>Read access to Dataplex Universal Catalog resources, except for catalog resources like entries, entry groups, and glossaries.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  analyzeIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.assetActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.get</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.list</code></p>
<p><code dir="ltr" translate="no">dataplex.content.get</code></p>
<p><code dir="ltr" translate="no">dataplex.content.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.content.list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAssets.get</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAssets.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAttributes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAttributes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataProducts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.list</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.list</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  environments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.list</code></p>
<p><code dir="ltr" translate="no">dataplex.lakeActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.list</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.get</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.list</code></p>
<p><code dir="ltr" translate="no">dataplex.zoneActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.get</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.aspectTypeOwner" class="role-title add-link" data-text="Dataplex Aspect Type Owner" tabindex="-1">Dataplex Aspect Type Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p>Grants access to creating and managing Aspect Types. Does not give the right to create/modify Entries.</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
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
<td><h4 id="dataplex.aspectTypeUser" class="role-title add-link" data-text="Dataplex Aspect Type User" tabindex="-1">Dataplex Aspect Type User</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.aspectTypeUser</code> )</p>
<p>Grants access to use Aspect Types to create/modify Entries with the corresponding aspects.</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.use</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.bindingAdmin" class="role-title add-link" data-text="Dataplex Binding Administrator" tabindex="-1">Dataplex Binding Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.bindingAdmin</code> )</p>
<p>Full access on DataAttribute Binding resources.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  create</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  delete</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  get</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  list</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.catalogAdmin" class="role-title add-link" data-text="Dataplex Catalog Admin" tabindex="-1">Dataplex Catalog Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p>Full access to catalog resources, including entries, entry groups, and glossaries.</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
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
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.catalogEditor" class="role-title add-link" data-text="Dataplex Catalog Editor" tabindex="-1">Dataplex Catalog Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p>Write access to catalog resources, including entries, entry groups, and glossaries. Cannot set IAM policies on resources.</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.create</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  aspectTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.update</code></p>
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
<p><code dir="ltr" translate="no">dataplex.entryGroups.create</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.update</code></p>
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
<p><code dir="ltr" translate="no">dataplex.entryLinks.create</code></p>
<p><code dir="ltr" translate="no">dataplex.entryLinks.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.entryLinks.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entryLinks.update</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.create</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.update</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.use</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaries.create</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaries.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaries.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  glossaries.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaries.list</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaries.update</code></p>
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
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.catalogViewer" class="role-title add-link" data-text="Dataplex Catalog Viewer" tabindex="-1">Dataplex Catalog Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p>Read access to catalog resources, including entries, entry groups, and glossaries. Can view IAM policies on catalog resources.</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
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
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataOwner" class="role-title add-link" data-text="Dataplex Data Owner" tabindex="-1">Dataplex Data Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.dataOwner</code> )</p>
<p>Owner access to data. To be granted to Dataplex Universal Catalog resources Lake, Zone or Asset only.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.assets.ownData</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.readData</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.writeData</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataProductsAdmin" class="role-title add-link" data-text="Dataplex Data Products Admin" tabindex="-1">Dataplex Data Products Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p>Full access to Data Products.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.dataAssets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.dataAssets.create</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.get</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.list</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.dataProducts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.dataProducts.create</code></li>
<li><code dir="ltr" translate="no">dataplex.dataProducts.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.dataProducts.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataProducts.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.dataProducts.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataProducts.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.dataProducts.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataProductsConsumer" class="role-title add-link" data-text="Dataplex Data Products Consumer" tabindex="-1">Dataplex Data Products Consumer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.dataProductsConsumer</code> )</p>
<p>Restricted read access, intended for consumers of Data Products.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.dataAssets.get</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAssets.list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataProductsEditor" class="role-title add-link" data-text="Dataplex Data Products Editor" tabindex="-1">Dataplex Data Products Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p>
<p>Write access to Data Products.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.dataAssets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.dataAssets.create</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.get</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.list</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAssets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.dataProducts.create</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataProducts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.update</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataProductsViewer" class="role-title add-link" data-text="Dataplex Data Products Viewer" tabindex="-1">Dataplex Data Products Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.dataProductsViewer</code> )</p>
<p>Read access to Data Products.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.dataAssets.get</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAssets.list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataProducts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataReader" class="role-title add-link" data-text="Dataplex Data Reader" tabindex="-1">Dataplex Data Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.dataReader</code> )</p>
<p>Read only access to data. To be granted to Dataplex Universal Catalog resources Lake, Zone or Asset only.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.assets.readData</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataScanCreator" class="role-title add-link" data-text="Dataplex DataScan Creator" tabindex="-1">Dataplex DataScan Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.dataScanCreator</code> )</p>
<p>Access to create new DataScan resources.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.datascans.create</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.get</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.list</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataScanDataViewer" class="role-title add-link" data-text="Dataplex DataScan DataViewer" tabindex="-1">Dataplex DataScan DataViewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.dataScanDataViewer</code> )</p>
<p>Read access to DataScan resources, including the results.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.datascans.get</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.getData</code></p>
<p><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataScanEditor" class="role-title add-link" data-text="Dataplex DataScan Editor" tabindex="-1">Dataplex DataScan Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.dataScanEditor</code> )</p>
<p>Write access to DataScan resources.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.datascans.cancel</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.create</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.get</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.getData</code></p>
<p><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.list</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.run</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.update</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataScanViewer" class="role-title add-link" data-text="Dataplex DataScan Viewer" tabindex="-1">Dataplex DataScan Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.dataScanViewer</code> )</p>
<p>Read access to DataScan resources, excluding the results.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.datascans.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataWriter" class="role-title add-link" data-text="Dataplex Data Writer" tabindex="-1">Dataplex Data Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.dataWriter</code> )</p>
<p>Write access to data. To be granted to Dataplex Universal Catalog resources Lake, Zone or Asset only.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.assets.writeData</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.developer" class="role-title add-link" data-text="Dataplex Developer" tabindex="-1">Dataplex Developer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.developer</code> )</p>
<p>Allows running data analytics workloads in a lake.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.content.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.content.create</code></li>
<li><code dir="ltr" translate="no">dataplex.content.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.content.get</code></li>
<li><code dir="ltr" translate="no">dataplex.content.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.content.list</code></li>
<li><code dir="ltr" translate="no">dataplex.content.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.content.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.environments.execute</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.get</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.list</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.cancel</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.create</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.get</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.list</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.run</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.encryptionAdmin" class="role-title add-link" data-text="Dataplex Encryption Admin" tabindex="-1">Dataplex Encryption Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.encryptionAdmin</code> )</p>
<p>Gives user permissions to manage encryption configurations.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.encryptionConfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.  encryptionConfig.  create</code></li>
<li><code dir="ltr" translate="no">dataplex.  encryptionConfig.  delete</code></li>
<li><code dir="ltr" translate="no">dataplex.encryptionConfig.get</code></li>
<li><code dir="ltr" translate="no">dataplex.encryptionConfig.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  encryptionConfig.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroupExporter" class="role-title add-link" data-text="Dataplex Entry Group Exporter" tabindex="-1">Dataplex Entry Group Exporter</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.entryGroupExporter</code> )</p>
<p>Grants access to export this entry group for Metadata Job processing.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.entryGroups.export</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroupImporter" class="role-title add-link" data-text="Dataplex Entry Group Importer" tabindex="-1">Dataplex Entry Group Importer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.entryGroupImporter</code> )</p>
<p>Grants access to import this entry group for Metadata Job processing.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.entryGroups.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.import</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroupOwner" class="role-title add-link" data-text="Dataplex Entry Group Owner" tabindex="-1">Dataplex Entry Group Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p>Owns Entry Groups and Entries inside of them.</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
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
<td><h4 id="dataplex.entryOwner" class="role-title add-link" data-text="Dataplex Entry and EntryLink Owner" tabindex="-1">Dataplex Entry and EntryLink Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Owns Metadata Entries and EntryLinks.</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
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
<td><h4 id="dataplex.entryTypeOwner" class="role-title add-link" data-text="Dataplex Entry Type Owner" tabindex="-1">Dataplex Entry Type Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p>
<p>Grants access to creating and managing Entry Types. Does not give the right to create/modify Entries.</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
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
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryTypeUser" class="role-title add-link" data-text="Dataplex Entry Type User" tabindex="-1">Dataplex Entry Type User</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.entryTypeUser</code> )</p>
<p>Grants access to use Entry Types to create/modify Entries of those types.</p></td>
<td><p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.use</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.metadataFeedOwner" class="role-title add-link" data-text="Dataplex Metadata Feed Owner" tabindex="-1">Dataplex Metadata Feed Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.metadataFeedOwner</code> )</p>
<p>Grants access to creating and managing Metadata Feeds. Does not give the right to create/modify Entry Groups.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.metadataFeeds.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.metadataFeeds.create</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataFeeds.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataFeeds.get</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataFeeds.list</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataFeeds.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.metadataFeedViewer" class="role-title add-link" data-text="Dataplex Metadata Feed Viewer" tabindex="-1">Dataplex Metadata Feed Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.metadataFeedViewer</code> )</p>
<p>Read access to Metadata Feed resources.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.metadataFeeds.get</code></p>
<p><code dir="ltr" translate="no">dataplex.metadataFeeds.list</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.metadataJobOwner" class="role-title add-link" data-text="Dataplex Metadata Job Owner" tabindex="-1">Dataplex Metadata Job Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.metadataJobOwner</code> )</p>
<p>Grants access to creating and managing Metadata Jobs. Does not give the right to create/modify Entry Groups.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.metadataJobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.metadataJobs.cancel</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataJobs.create</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataJobs.get</code></li>
<li><code dir="ltr" translate="no">dataplex.metadataJobs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.metadataJobViewer" class="role-title add-link" data-text="Dataplex Metadata Job Viewer" tabindex="-1">Dataplex Metadata Job Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.metadataJobViewer</code> )</p>
<p>Read access to Metadata Job resources.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.metadataJobs.get</code></p>
<p><code dir="ltr" translate="no">dataplex.metadataJobs.list</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.metadataReader" class="role-title add-link" data-text="Dataplex Metadata Reader" tabindex="-1">Dataplex Metadata Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.metadataReader</code> )</p>
<p>Read only access to metadata within table and fileset entities and partitions.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.assets.get</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entities.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entities.list</code></p>
<p><code dir="ltr" translate="no">dataplex.partitions.get</code></p>
<p><code dir="ltr" translate="no">dataplex.partitions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.get</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.metadataWriter" class="role-title add-link" data-text="Dataplex Metadata Writer" tabindex="-1">Dataplex Metadata Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p>
<p>Write and read access to metadata within table and fileset entities and partitions.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.assets.get</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.entities.create</code></li>
<li><code dir="ltr" translate="no">dataplex.entities.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.entities.get</code></li>
<li><code dir="ltr" translate="no">dataplex.entities.list</code></li>
<li><code dir="ltr" translate="no">dataplex.entities.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.partitions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.partitions.create</code></li>
<li><code dir="ltr" translate="no">dataplex.partitions.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.partitions.get</code></li>
<li><code dir="ltr" translate="no">dataplex.partitions.list</code></li>
<li><code dir="ltr" translate="no">dataplex.partitions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.zones.get</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.securityAdmin" class="role-title add-link" data-text="Dataplex Security Administrator" tabindex="-1">Dataplex Security Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.securityAdmin</code> )</p>
<p>Permissions configure ResourceAccess and DataAccess Specs on Data Attributes.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  configureDataAccess</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  configureResourceAccess</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.storageDataOwner" class="role-title add-link" data-text="Dataplex Storage Data Owner" tabindex="-1">Dataplex Storage Data Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.storageDataOwner</code> )</p>
<p>Owner access to data. Should not be used directly. This role is granted by Dataplex to managed resources like Cloud Storage buckets, BigQuery datasets etc.</p></td>
<td><p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.models.create</code></p>
<p><code dir="ltr" translate="no">bigquery.models.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.models.export</code></p>
<p><code dir="ltr" translate="no">bigquery.models.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.models.getMetadata</code></p>
<p><code dir="ltr" translate="no">bigquery.models.list</code></p>
<p><code dir="ltr" translate="no">bigquery.models.updateData</code></p>
<p><code dir="ltr" translate="no">bigquery.models.updateMetadata</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.create</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.get</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.list</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.createSnapshot</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.deleteSnapshot</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.export</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  restoreSnapshot</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.storageDataReader" class="role-title add-link" data-text="Dataplex Storage Data Reader" tabindex="-1">Dataplex Storage Data Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.storageDataReader</code> )</p>
<p>Read only access to data. Should not be used directly. This role is granted by Dataplex to managed resources like Cloud Storage buckets, BigQuery datasets etc.</p></td>
<td><p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.models.export</code></p>
<p><code dir="ltr" translate="no">bigquery.models.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.models.getMetadata</code></p>
<p><code dir="ltr" translate="no">bigquery.models.list</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.get</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.export</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.storageDataWriter" class="role-title add-link" data-text="Dataplex Storage Data Writer" tabindex="-1">Dataplex Storage Data Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.storageDataWriter</code> )</p>
<p>Write access to data. Should not be used directly. This role is granted by Dataplex to managed resources like Cloud Storage buckets, BigQuery datasets etc.</p></td>
<td><p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.taxonomyAdmin" class="role-title add-link" data-text="Dataplex Taxonomy Administrator" tabindex="-1">Dataplex Taxonomy Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p>
<p>Full access to DataTaxonomy, DataAttribute resources.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.dataAttributes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.dataAttributes.bind</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAttributes.create</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAttributes.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAttributes.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAttributes.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  dataAttributes.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.dataAttributes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.create</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.taxonomyViewer" class="role-title add-link" data-text="Dataplex Taxonomy Viewer" tabindex="-1">Dataplex Taxonomy Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.taxonomyViewer</code> )</p>
<p>Read access on DataTaxonomy, DataAttribute resources.</p></td>
<td><p><code dir="ltr" translate="no">dataplex.dataAttributes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAttributes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.get</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.list</code></p></td>
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
<td><h4 id="dataplex.discoveryBigLakePublishingServiceAgent" class="role-title add-link" data-text="Dataplex Discovery BigLake Publishing Service Agent" tabindex="-1">Dataplex Discovery BigLake Publishing Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.discoveryBigLakePublishingServiceAgent</code> )</p>
<p>Gives the Dataplex Discovery Service Agent permissions to use bigquery connection.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.connections.delegate</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.use</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.discoveryPublishingServiceAgent" class="role-title add-link" data-text="Dataplex Discovery Publishing Service Agent" tabindex="-1">Dataplex Discovery Publishing Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.discoveryPublishingServiceAgent</code> )</p>
<p>Gives the Dataplex Discovery Service Agent dataset create and get permissions.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.discoveryServiceAgent" class="role-title add-link" data-text="Dataplex Discovery Service Agent" tabindex="-1">Dataplex Discovery Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.discoveryServiceAgent</code> )</p>
<p>Gives the Dataplex Discovery Service Agent bucket read permissions.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.serviceAgent" class="role-title add-link" data-text="Cloud Dataplex Service Agent" tabindex="-1">Cloud Dataplex Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</p>
<p>Gives the Dataplex service account access to project resources. This access will be used in data discovery, data management and data workload management.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">biglake.catalogs.get</code></p>
<p><code dir="ltr" translate="no">biglake.namespaces.get</code></p>
<p><code dir="ltr" translate="no">biglake.tables.get</code></p>
<p><code dir="ltr" translate="no">biglake.tables.getData</code></p>
<p><code dir="ltr" translate="no">biglake.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.bireservations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.bireservations.get</code></li>
<li><code dir="ltr" translate="no">bigquery.bireservations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.capacityCommitments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.  capacityCommitments.  create</code></li>
<li><code dir="ltr" translate="no">bigquery.  capacityCommitments.  delete</code></li>
<li><code dir="ltr" translate="no">bigquery.  capacityCommitments.  get</code></li>
<li><code dir="ltr" translate="no">bigquery.  capacityCommitments.  list</code></li>
<li><code dir="ltr" translate="no">bigquery.  capacityCommitments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.config.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.config.get</code></li>
<li><code dir="ltr" translate="no">bigquery.config.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.connections.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.connections.create</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.delegate</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.get</code></li>
<li><code dir="ltr" translate="no">bigquery.  connections.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.list</code></li>
<li><code dir="ltr" translate="no">bigquery.  connections.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.update</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.updateTag</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.use</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.attach</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.create</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  dataPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  dataPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.update</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.datasets.create</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.get</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.link</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  listSharedDatasetUsage</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.update</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.jobs.create</code></li>
<li><code dir="ltr" translate="no">bigquery.  jobs.  createGlobalQuery</code></li>
<li><code dir="ltr" translate="no">bigquery.jobs.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.jobs.get</code></li>
<li><code dir="ltr" translate="no">bigquery.jobs.list</code></li>
<li><code dir="ltr" translate="no">bigquery.jobs.listAll</code></li>
<li><code dir="ltr" translate="no">bigquery.  jobs.  listExecutionMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.jobs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.models.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.models.create</code></li>
<li><code dir="ltr" translate="no">bigquery.models.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.models.export</code></li>
<li><code dir="ltr" translate="no">bigquery.models.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.models.getMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.models.list</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateData</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.objectRefs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.objectRefs.read</code></li>
<li><code dir="ltr" translate="no">bigquery.objectRefs.write</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.readsessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.readsessions.create</code></li>
<li><code dir="ltr" translate="no">bigquery.readsessions.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.readsessions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.  reservationAssignments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.  reservationAssignments.  create</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservationAssignments.  delete</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservationAssignments.  list</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservationAssignments.  search</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.reservationGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.  reservationGroups.  create</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservationGroups.  delete</code></li>
<li><code dir="ltr" translate="no">bigquery.reservationGroups.get</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservationGroups.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.reservations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.reservations.create</code></li>
<li><code dir="ltr" translate="no">bigquery.reservations.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.reservations.get</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservations.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.reservations.list</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservations.  listFailoverDatasets</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservations.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.reservations.update</code></li>
<li><code dir="ltr" translate="no">bigquery.reservations.use</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.routines.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.routines.create</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.get</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.list</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.update</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  create</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">bigquery.rowAccessPolicies.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  overrideTimeTravelRestrictions</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  update</code></p>
<p><code dir="ltr" translate="no">bigquery.savedqueries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.savedqueries.create</code></li>
<li><code dir="ltr" translate="no">bigquery.savedqueries.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.savedqueries.get</code></li>
<li><code dir="ltr" translate="no">bigquery.savedqueries.list</code></li>
<li><code dir="ltr" translate="no">bigquery.savedqueries.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.tables.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.tables.create</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.createIndex</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.createSnapshot</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.deleteIndex</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.deleteSnapshot</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.export</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.get</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.list</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.replicateData</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  restoreSnapshot</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.setCategory</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  setColumnDataPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.update</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.updateData</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.updateIndex</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.transfers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.transfers.get</code></li>
<li><code dir="ltr" translate="no">bigquery.transfers.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquerymigration.  translation.  translate</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  completeTask</code></p>
<p><code dir="ltr" translate="no">datacatalog.catalogs.searchAll</code></p>
<p><code dir="ltr" translate="no">datacatalog.  categories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.  categories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.create</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.delete</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.update</code></p>
<p><code dir="ltr" translate="no">dataform.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.commentThreads.create</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.delete</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.get</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.list</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.update</code></li>
<li><code dir="ltr" translate="no">dataform.comments.create</code></li>
<li><code dir="ltr" translate="no">dataform.comments.delete</code></li>
<li><code dir="ltr" translate="no">dataform.comments.get</code></li>
<li><code dir="ltr" translate="no">dataform.comments.list</code></li>
<li><code dir="ltr" translate="no">dataform.comments.update</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></li>
<li><code dir="ltr" translate="no">dataform.config.get</code></li>
<li><code dir="ltr" translate="no">dataform.config.update</code></li>
<li><code dir="ltr" translate="no">dataform.folders.addContents</code></li>
<li><code dir="ltr" translate="no">dataform.folders.create</code></li>
<li><code dir="ltr" translate="no">dataform.folders.delete</code></li>
<li><code dir="ltr" translate="no">dataform.folders.deleteTree</code></li>
<li><code dir="ltr" translate="no">dataform.folders.get</code></li>
<li><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.folders.move</code></li>
<li><code dir="ltr" translate="no">dataform.folders.queryContents</code></li>
<li><code dir="ltr" translate="no">dataform.folders.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.folders.update</code></li>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
<li><code dir="ltr" translate="no">dataform.operations.cancel</code></li>
<li><code dir="ltr" translate="no">dataform.operations.delete</code></li>
<li><code dir="ltr" translate="no">dataform.operations.get</code></li>
<li><code dir="ltr" translate="no">dataform.operations.list</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.create</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.delete</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.get</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.list</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.update</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.commit</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.create</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.delete</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.get</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.list</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.move</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.readFile</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  scheduleRelease</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  scheduleWorkflow</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.update</code></li>
<li><code dir="ltr" translate="no">dataform.teamFolders.create</code></li>
<li><code dir="ltr" translate="no">dataform.teamFolders.delete</code></li>
<li><code dir="ltr" translate="no">dataform.  teamFolders.  deleteTree</code></li>
<li><code dir="ltr" translate="no">dataform.teamFolders.get</code></li>
<li><code dir="ltr" translate="no">dataform.  teamFolders.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.  teamFolders.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.teamFolders.update</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowConfigs.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">dataform.workflowConfigs.get</code></li>
<li><code dir="ltr" translate="no">dataform.workflowConfigs.list</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowConfigs.  update</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  cancel</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  delete</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  query</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.commit</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.create</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.delete</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.get</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  installNpmPackages</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.list</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  makeDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  moveDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.moveFile</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.pull</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.push</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.readFile</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  removeDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.removeFile</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.reset</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.writeFile</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.assets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.datascans.cancel</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.create</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.get</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.getData</code></li>
<li><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.list</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.run</code></li>
<li><code dir="ltr" translate="no">dataplex.  datascans.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.environments.execute</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.get</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.list</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.list</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.batches.cancel</code></p>
<p><code dir="ltr" translate="no">dataproc.batches.create</code></p>
<p><code dir="ltr" translate="no">dataproc.batches.get</code></p>
<p><code dir="ltr" translate="no">dataproc.operations.cancel</code></p>
<p><code dir="ltr" translate="no">dataproc.operations.get</code></p>
<p><code dir="ltr" translate="no">dataproc.operations.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">metastore.services.get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.timeSeries.create</code></li>
<li><code dir="ltr" translate="no">monitoring.timeSeries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  report</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">storage.anywhereCaches.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.anywhereCaches.create</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.disable</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.get</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.list</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.pause</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.resume</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.bucketOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.  bucketOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">storage.bucketOperations.get</code></li>
<li><code dir="ltr" translate="no">storage.bucketOperations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.buckets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.buckets.create</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">storage.buckets.delete</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  enableObjectRetention</code></li>
<li><code dir="ltr" translate="no">storage.buckets.get</code></li>
<li><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.buckets.getIpFilter</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  getObjectInsights</code></li>
<li><code dir="ltr" translate="no">storage.buckets.list</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">storage.buckets.relocate</code></li>
<li><code dir="ltr" translate="no">storage.buckets.restore</code></li>
<li><code dir="ltr" translate="no">storage.buckets.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.buckets.setIpFilter</code></li>
<li><code dir="ltr" translate="no">storage.buckets.update</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  viewIntelligenceDetails</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.featureConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.featureConfigs.create</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.delete</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.get</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.list</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.folders.create</code></li>
<li><code dir="ltr" translate="no">storage.folders.delete</code></li>
<li><code dir="ltr" translate="no">storage.folders.get</code></li>
<li><code dir="ltr" translate="no">storage.folders.list</code></li>
<li><code dir="ltr" translate="no">storage.folders.rename</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.intelligenceConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.  intelligenceConfigs.  get</code></li>
<li><code dir="ltr" translate="no">storage.  intelligenceConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.managedFolders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.managedFolders.create</code></li>
<li><code dir="ltr" translate="no">storage.managedFolders.delete</code></li>
<li><code dir="ltr" translate="no">storage.managedFolders.get</code></li>
<li><code dir="ltr" translate="no">storage.  managedFolders.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.managedFolders.list</code></li>
<li><code dir="ltr" translate="no">storage.  managedFolders.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.multipartUploads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.multipartUploads.abort</code></li>
<li><code dir="ltr" translate="no">storage.  multipartUploads.  create</code></li>
<li><code dir="ltr" translate="no">storage.multipartUploads.list</code></li>
<li><code dir="ltr" translate="no">storage.  multipartUploads.  listParts</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.objects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.objects.create</code></li>
<li><code dir="ltr" translate="no">storage.objects.createContext</code></li>
<li><code dir="ltr" translate="no">storage.objects.delete</code></li>
<li><code dir="ltr" translate="no">storage.objects.deleteContext</code></li>
<li><code dir="ltr" translate="no">storage.objects.get</code></li>
<li><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.objects.list</code></li>
<li><code dir="ltr" translate="no">storage.objects.move</code></li>
<li><code dir="ltr" translate="no">storage.  objects.  overrideUnlockedRetention</code></li>
<li><code dir="ltr" translate="no">storage.objects.restore</code></li>
<li><code dir="ltr" translate="no">storage.objects.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.objects.setRetention</code></li>
<li><code dir="ltr" translate="no">storage.objects.update</code></li>
<li><code dir="ltr" translate="no">storage.objects.updateContext</code></li>
</ul>
<p><code dir="ltr" translate="no">storagebatchoperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storagebatchoperations.  bucketOperations.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  bucketOperations.  list</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  cancel</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  create</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  delete</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  list</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  locations.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  locations.  list</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Knowledge Catalog permissions

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
<td><h4 id="dataplex.aspectTypes.create" class="permission-name add-link" data-text="dataplex.aspectTypes.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.aspectTypes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateCreator">Data Catalog TagTemplate Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
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
<td><h4 id="dataplex.aspectTypes.delete" class="permission-name add-link" data-text="dataplex.aspectTypes.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.aspectTypes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.aspectTypes.get" class="permission-name add-link" data-text="dataplex.aspectTypes.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateCreator">Data Catalog TagTemplate Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
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
<tr class="even">
<td><h4 id="dataplex.aspectTypes.getIamPolicy" class="permission-name add-link" data-text="dataplex.aspectTypes.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  aspectTypes.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
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
<tr class="odd">
<td><h4 id="dataplex.aspectTypes.list" class="permission-name add-link" data-text="dataplex.aspectTypes.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
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
<td><h4 id="dataplex.aspectTypes.setIamPolicy" class="permission-name add-link" data-text="dataplex.aspectTypes.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  aspectTypes.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.aspectTypes.update" class="permission-name add-link" data-text="dataplex.aspectTypes.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.aspectTypes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.aspectTypes.use" class="permission-name add-link" data-text="dataplex.aspectTypes.use" tabindex="-1"><code dir="ltr" translate="no">dataplex.aspectTypes.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
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
<td><h4 id="dataplex.assetActions.list" class="permission-name add-link" data-text="dataplex.assetActions.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.assetActions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.assets.create" class="permission-name add-link" data-text="dataplex.assets.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.assets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.assets.delete" class="permission-name add-link" data-text="dataplex.assets.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.assets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.assets.get" class="permission-name add-link" data-text="dataplex.assets.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.assets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.assets.getIamPolicy" class="permission-name add-link" data-text="dataplex.assets.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.assets.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
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
<td><h4 id="dataplex.assets.list" class="permission-name add-link" data-text="dataplex.assets.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.assets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.assets.ownData" class="permission-name add-link" data-text="dataplex.assets.ownData" tabindex="-1"><code dir="ltr" translate="no">dataplex.assets.ownData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataOwner">Dataplex Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.assets.readData" class="permission-name add-link" data-text="dataplex.assets.readData" tabindex="-1"><code dir="ltr" translate="no">dataplex.assets.readData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataOwner">Dataplex Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataReader">Dataplex Data Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.assets.setIamPolicy" class="permission-name add-link" data-text="dataplex.assets.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.assets.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.assets.update" class="permission-name add-link" data-text="dataplex.assets.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.assets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.assets.writeData" class="permission-name add-link" data-text="dataplex.assets.writeData" tabindex="-1"><code dir="ltr" translate="no">dataplex.assets.writeData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataOwner">Dataplex Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataWriter">Dataplex Data Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.content.create" class="permission-name add-link" data-text="dataplex.content.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.content.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.content.delete" class="permission-name add-link" data-text="dataplex.content.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.content.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.content.get" class="permission-name add-link" data-text="dataplex.content.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.content.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.content.getIamPolicy" class="permission-name add-link" data-text="dataplex.content.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.content.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.content.list" class="permission-name add-link" data-text="dataplex.content.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.content.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.content.setIamPolicy" class="permission-name add-link" data-text="dataplex.content.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.content.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.content.update" class="permission-name add-link" data-text="dataplex.content.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.content.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataAssets.create" class="permission-name add-link" data-text="dataplex.dataAssets.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataAssets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataAssets.delete" class="permission-name add-link" data-text="dataplex.dataAssets.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataAssets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataAssets.get" class="permission-name add-link" data-text="dataplex.dataAssets.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataAssets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsConsumer">Dataplex Data Products Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataAssets.list" class="permission-name add-link" data-text="dataplex.dataAssets.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataAssets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsConsumer">Dataplex Data Products Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataAssets.update" class="permission-name add-link" data-text="dataplex.dataAssets.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataAssets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataAttributeBindings.create" class="permission-name add-link" data-text="dataplex.dataAttributeBindings.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.bindingAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataAttributeBindings.delete" class="permission-name add-link" data-text="dataplex.dataAttributeBindings.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.bindingAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataAttributeBindings.get" class="permission-name add-link" data-text="dataplex.dataAttributeBindings.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.bindingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataAttributeBindings.getIamPolicy" class="permission-name add-link" data-text="dataplex.dataAttributeBindings.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.bindingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataAttributeBindings.list" class="permission-name add-link" data-text="dataplex.dataAttributeBindings.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.bindingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataAttributeBindings.setIamPolicy" class="permission-name add-link" data-text="dataplex.dataAttributeBindings.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.bindingAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataAttributeBindings.update" class="permission-name add-link" data-text="dataplex.dataAttributeBindings.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.bindingAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataAttributes.bind" class="permission-name add-link" data-text="dataplex.dataAttributes.bind" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataAttributes.bind</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataAttributes.create" class="permission-name add-link" data-text="dataplex.dataAttributes.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataAttributes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataAttributes.delete" class="permission-name add-link" data-text="dataplex.dataAttributes.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataAttributes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataAttributes.get" class="permission-name add-link" data-text="dataplex.dataAttributes.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataAttributes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyViewer">Dataplex Taxonomy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataAttributes.getIamPolicy" class="permission-name add-link" data-text="dataplex.dataAttributes.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataAttributes.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyViewer">Dataplex Taxonomy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataAttributes.list" class="permission-name add-link" data-text="dataplex.dataAttributes.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataAttributes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyViewer">Dataplex Taxonomy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataAttributes.setIamPolicy" class="permission-name add-link" data-text="dataplex.dataAttributes.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataAttributes.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataAttributes.update" class="permission-name add-link" data-text="dataplex.dataAttributes.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataAttributes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataProducts.create" class="permission-name add-link" data-text="dataplex.dataProducts.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataProducts.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataProducts.delete" class="permission-name add-link" data-text="dataplex.dataProducts.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataProducts.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataProducts.get" class="permission-name add-link" data-text="dataplex.dataProducts.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataProducts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsConsumer">Dataplex Data Products Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataProducts.getIamPolicy" class="permission-name add-link" data-text="dataplex.dataProducts.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataProducts.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataProducts.list" class="permission-name add-link" data-text="dataplex.dataProducts.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataProducts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataProducts.setIamPolicy" class="permission-name add-link" data-text="dataplex.dataProducts.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataProducts.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataProducts.update" class="permission-name add-link" data-text="dataplex.dataProducts.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataProducts.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataTaxonomies.configureDataAccess" class="permission-name add-link" data-text="dataplex.dataTaxonomies.configureDataAccess" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  configureDataAccess</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.securityAdmin">Dataplex Security Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataTaxonomies.configureResourceAccess" class="permission-name add-link" data-text="dataplex.dataTaxonomies.configureResourceAccess" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  configureResourceAccess</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.securityAdmin">Dataplex Security Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataTaxonomies.create" class="permission-name add-link" data-text="dataplex.dataTaxonomies.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataTaxonomies.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataTaxonomies.delete" class="permission-name add-link" data-text="dataplex.dataTaxonomies.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataTaxonomies.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataTaxonomies.get" class="permission-name add-link" data-text="dataplex.dataTaxonomies.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataTaxonomies.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyViewer">Dataplex Taxonomy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataTaxonomies.getIamPolicy" class="permission-name add-link" data-text="dataplex.dataTaxonomies.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyViewer">Dataplex Taxonomy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataTaxonomies.list" class="permission-name add-link" data-text="dataplex.dataTaxonomies.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataTaxonomies.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyViewer">Dataplex Taxonomy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.dataTaxonomies.setIamPolicy" class="permission-name add-link" data-text="dataplex.dataTaxonomies.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.dataTaxonomies.update" class="permission-name add-link" data-text="dataplex.dataTaxonomies.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.dataTaxonomies.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.taxonomyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.datascans.cancel" class="permission-name add-link" data-text="dataplex.datascans.cancel" tabindex="-1"><code dir="ltr" translate="no">dataplex.datascans.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.datascans.create" class="permission-name add-link" data-text="dataplex.datascans.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.datascans.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanCreator">Dataplex DataScan Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.datascans.delete" class="permission-name add-link" data-text="dataplex.datascans.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.datascans.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.datascans.get" class="permission-name add-link" data-text="dataplex.datascans.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.datascans.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataViewer">BigQuery Data Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanCreator">Dataplex DataScan Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanDataViewer">Dataplex DataScan DataViewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanDataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanViewer">Dataplex DataScan Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.datascans.getData" class="permission-name add-link" data-text="dataplex.datascans.getData" tabindex="-1"><code dir="ltr" translate="no">dataplex.datascans.getData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataViewer">BigQuery Data Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanDataViewer">Dataplex DataScan DataViewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanDataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.datascans.getIamPolicy" class="permission-name add-link" data-text="dataplex.datascans.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataViewer">BigQuery Data Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanDataViewer">Dataplex DataScan DataViewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanDataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanViewer">Dataplex DataScan Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.datascans.list" class="permission-name add-link" data-text="dataplex.datascans.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.datascans.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataViewer">BigQuery Data Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanCreator">Dataplex DataScan Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanDataViewer">Dataplex DataScan DataViewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanDataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanViewer">Dataplex DataScan Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.datascans.run" class="permission-name add-link" data-text="dataplex.datascans.run" tabindex="-1"><code dir="ltr" translate="no">dataplex.datascans.run</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.datascans.setIamPolicy" class="permission-name add-link" data-text="dataplex.datascans.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  datascans.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.datascans.update" class="permission-name add-link" data-text="dataplex.datascans.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.datascans.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.encryptionConfig.create" class="permission-name add-link" data-text="dataplex.encryptionConfig.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.  encryptionConfig.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.encryptionAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.encryptionConfig.delete" class="permission-name add-link" data-text="dataplex.encryptionConfig.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.  encryptionConfig.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.encryptionAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.encryptionConfig.get" class="permission-name add-link" data-text="dataplex.encryptionConfig.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.encryptionConfig.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.encryptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.encryptionConfig.list" class="permission-name add-link" data-text="dataplex.encryptionConfig.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.encryptionConfig.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.encryptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.encryptionConfig.update" class="permission-name add-link" data-text="dataplex.encryptionConfig.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.  encryptionConfig.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.encryptionAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entities.create" class="permission-name add-link" data-text="dataplex.entities.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.entities.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entities.delete" class="permission-name add-link" data-text="dataplex.entities.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.entities.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entities.get" class="permission-name add-link" data-text="dataplex.entities.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.entities.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entities.list" class="permission-name add-link" data-text="dataplex.entities.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.entities.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entities.update" class="permission-name add-link" data-text="dataplex.entities.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.entities.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entries.create" class="permission-name add-link" data-text="dataplex.entries.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.entries.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entries.delete" class="permission-name add-link" data-text="dataplex.entries.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.entries.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entries.get" class="permission-name add-link" data-text="dataplex.entries.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.entries.get</code></h4></td>
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
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
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
<tr class="even">
<td><h4 id="dataplex.entries.getData" class="permission-name add-link" data-text="dataplex.entries.getData" tabindex="-1"><code dir="ltr" translate="no">dataplex.entries.getData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entries.link" class="permission-name add-link" data-text="dataplex.entries.link" tabindex="-1"><code dir="ltr" translate="no">dataplex.entries.link</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entries.list" class="permission-name add-link" data-text="dataplex.entries.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.entries.list</code></h4></td>
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
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entries.update" class="permission-name add-link" data-text="dataplex.entries.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.entries.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagEditor">Data Catalog Tag Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.create" class="permission-name add-link" data-text="dataplex.entryGroups.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryGroups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.delete" class="permission-name add-link" data-text="dataplex.entryGroups.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryGroups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.export" class="permission-name add-link" data-text="dataplex.entryGroups.export" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryGroups.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupExporter">Dataplex Entry Group Exporter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupExporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.get" class="permission-name add-link" data-text="dataplex.entryGroups.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryGroups.get</code></h4></td>
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
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupExporter">Dataplex Entry Group Exporter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupExporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupImporter">Dataplex Entry Group Importer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupImporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.getIamPolicy" class="permission-name add-link" data-text="dataplex.entryGroups.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.import" class="permission-name add-link" data-text="dataplex.entryGroups.import" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryGroups.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupImporter">Dataplex Entry Group Importer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupImporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.list" class="permission-name add-link" data-text="dataplex.entryGroups.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryGroups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.setIamPolicy" class="permission-name add-link" data-text="dataplex.entryGroups.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.update" class="permission-name add-link" data-text="dataplex.entryGroups.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryGroups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useContactsAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useContactsAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useContactsAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useDataProfileAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useDataProfileAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataProfileAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useDataQualityRuleTemplateAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useDataQualityRuleTemplateAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataQualityRuleTemplateAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useDataQualityRuleTemplateEntry" class="permission-name add-link" data-text="dataplex.entryGroups.useDataQualityRuleTemplateEntry" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataQualityRuleTemplateEntry</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useDataQualityScorecardAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useDataQualityScorecardAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataQualityScorecardAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useDataRulesAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useDataRulesAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useDataRulesAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useDatabaseDataPolicyAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useDatabaseDataPolicyAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useDatabaseDataPolicyAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useDefinitionEntryLink" class="permission-name add-link" data-text="dataplex.entryGroups.useDefinitionEntryLink" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useDefinitionEntryLink</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useDescriptionsAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useDescriptionsAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useDescriptionsAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useGenericAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useGenericAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useGenericAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useGenericEntry" class="permission-name add-link" data-text="dataplex.entryGroups.useGenericEntry" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useGenericEntry</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useGraphProfileAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useGraphProfileAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useGraphProfileAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useMySQLConnectorTypes" class="permission-name add-link" data-text="dataplex.entryGroups.useMySQLConnectorTypes" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useMySQLConnectorTypes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useOracleConnectorTypes" class="permission-name add-link" data-text="dataplex.entryGroups.useOracleConnectorTypes" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useOracleConnectorTypes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useOverviewAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useOverviewAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useOverviewAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.usePostgreSQLConnectorTypes" class="permission-name add-link" data-text="dataplex.entryGroups.usePostgreSQLConnectorTypes" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  usePostgreSQLConnectorTypes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useQueriesAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useQueriesAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useQueriesAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useRefreshCadenceAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useRefreshCadenceAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useRefreshCadenceAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useRelatedEntryLink" class="permission-name add-link" data-text="dataplex.entryGroups.useRelatedEntryLink" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useRelatedEntryLink</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useSQLAccessAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useSQLAccessAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLAccessAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useSQLServerConnectorTypes" class="permission-name add-link" data-text="dataplex.entryGroups.useSQLServerConnectorTypes" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLServerConnectorTypes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useSQLTriggersAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useSQLTriggersAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useSQLTriggersAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useSchemaAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useSchemaAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useSchemaJoinAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useSchemaJoinAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaJoinAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useSchemaJoinEntryLink" class="permission-name add-link" data-text="dataplex.entryGroups.useSchemaJoinEntryLink" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useSchemaJoinEntryLink</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useSecondaryIndexesAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useSecondaryIndexesAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useSecondaryIndexesAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryGroups.useStorageAspect" class="permission-name add-link" data-text="dataplex.entryGroups.useStorageAspect" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useStorageAspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryGroups.useSynonymEntryLink" class="permission-name add-link" data-text="dataplex.entryGroups.useSynonymEntryLink" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryGroups.  useSynonymEntryLink</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryLinks.create" class="permission-name add-link" data-text="dataplex.entryLinks.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryLinks.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryLinks.delete" class="permission-name add-link" data-text="dataplex.entryLinks.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryLinks.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryLinks.get" class="permission-name add-link" data-text="dataplex.entryLinks.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryLinks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryLinks.reference" class="permission-name add-link" data-text="dataplex.entryLinks.reference" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryLinks.reference</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryLinks.update" class="permission-name add-link" data-text="dataplex.entryLinks.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryLinks.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryTypes.create" class="permission-name add-link" data-text="dataplex.entryTypes.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryTypes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryTypes.delete" class="permission-name add-link" data-text="dataplex.entryTypes.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryTypes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryTypes.get" class="permission-name add-link" data-text="dataplex.entryTypes.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryTypes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryTypes.getIamPolicy" class="permission-name add-link" data-text="dataplex.entryTypes.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryTypes.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryTypes.list" class="permission-name add-link" data-text="dataplex.entryTypes.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryTypes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryTypes.setIamPolicy" class="permission-name add-link" data-text="dataplex.entryTypes.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  entryTypes.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.entryTypes.update" class="permission-name add-link" data-text="dataplex.entryTypes.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryTypes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.entryTypes.use" class="permission-name add-link" data-text="dataplex.entryTypes.use" tabindex="-1"><code dir="ltr" translate="no">dataplex.entryTypes.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.environments.create" class="permission-name add-link" data-text="dataplex.environments.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.environments.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.environments.delete" class="permission-name add-link" data-text="dataplex.environments.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.environments.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.environments.execute" class="permission-name add-link" data-text="dataplex.environments.execute" tabindex="-1"><code dir="ltr" translate="no">dataplex.environments.execute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.environments.get" class="permission-name add-link" data-text="dataplex.environments.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.environments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p>
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
<td><h4 id="dataplex.environments.getIamPolicy" class="permission-name add-link" data-text="dataplex.environments.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  environments.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.environments.list" class="permission-name add-link" data-text="dataplex.environments.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.environments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p>
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
<td><h4 id="dataplex.environments.setIamPolicy" class="permission-name add-link" data-text="dataplex.environments.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  environments.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.environments.update" class="permission-name add-link" data-text="dataplex.environments.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.environments.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.glossaries.create" class="permission-name add-link" data-text="dataplex.glossaries.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.glossaries.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.glossaries.delete" class="permission-name add-link" data-text="dataplex.glossaries.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.glossaries.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.glossaries.get" class="permission-name add-link" data-text="dataplex.glossaries.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.glossaries.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.glossaries.getIamPolicy" class="permission-name add-link" data-text="dataplex.glossaries.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  glossaries.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.glossaries.import" class="permission-name add-link" data-text="dataplex.glossaries.import" tabindex="-1"><code dir="ltr" translate="no">dataplex.glossaries.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.glossaries.list" class="permission-name add-link" data-text="dataplex.glossaries.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.glossaries.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.glossaries.setIamPolicy" class="permission-name add-link" data-text="dataplex.glossaries.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.  glossaries.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.glossaries.update" class="permission-name add-link" data-text="dataplex.glossaries.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.glossaries.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.glossaryCategories.create" class="permission-name add-link" data-text="dataplex.glossaryCategories.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.  glossaryCategories.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.glossaryCategories.delete" class="permission-name add-link" data-text="dataplex.glossaryCategories.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.  glossaryCategories.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.glossaryCategories.get" class="permission-name add-link" data-text="dataplex.glossaryCategories.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.  glossaryCategories.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.glossaryCategories.list" class="permission-name add-link" data-text="dataplex.glossaryCategories.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.  glossaryCategories.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.glossaryCategories.update" class="permission-name add-link" data-text="dataplex.glossaryCategories.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.  glossaryCategories.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.glossaryTerms.create" class="permission-name add-link" data-text="dataplex.glossaryTerms.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.glossaryTerms.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.glossaryTerms.delete" class="permission-name add-link" data-text="dataplex.glossaryTerms.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.glossaryTerms.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.glossaryTerms.get" class="permission-name add-link" data-text="dataplex.glossaryTerms.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.glossaryTerms.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.glossaryTerms.list" class="permission-name add-link" data-text="dataplex.glossaryTerms.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.glossaryTerms.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.glossaryTerms.update" class="permission-name add-link" data-text="dataplex.glossaryTerms.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.glossaryTerms.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.glossaryTerms.use" class="permission-name add-link" data-text="dataplex.glossaryTerms.use" tabindex="-1"><code dir="ltr" translate="no">dataplex.glossaryTerms.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.lakeActions.list" class="permission-name add-link" data-text="dataplex.lakeActions.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.lakeActions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.lakes.create" class="permission-name add-link" data-text="dataplex.lakes.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.lakes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.lakes.delete" class="permission-name add-link" data-text="dataplex.lakes.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.lakes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.lakes.get" class="permission-name add-link" data-text="dataplex.lakes.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.lakes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
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
<td><h4 id="dataplex.lakes.getIamPolicy" class="permission-name add-link" data-text="dataplex.lakes.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.lakes.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
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
<td><h4 id="dataplex.lakes.list" class="permission-name add-link" data-text="dataplex.lakes.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.lakes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.lakes.setIamPolicy" class="permission-name add-link" data-text="dataplex.lakes.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.lakes.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.lakes.update" class="permission-name add-link" data-text="dataplex.lakes.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.lakes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.locations.get" class="permission-name add-link" data-text="dataplex.locations.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.locations.list" class="permission-name add-link" data-text="dataplex.locations.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.metadataFeeds.create" class="permission-name add-link" data-text="dataplex.metadataFeeds.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.metadataFeeds.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.metadataFeeds.delete" class="permission-name add-link" data-text="dataplex.metadataFeeds.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.metadataFeeds.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.metadataFeeds.get" class="permission-name add-link" data-text="dataplex.metadataFeeds.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.metadataFeeds.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedViewer">Dataplex Metadata Feed Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.metadataFeeds.list" class="permission-name add-link" data-text="dataplex.metadataFeeds.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.metadataFeeds.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedViewer">Dataplex Metadata Feed Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.metadataFeeds.update" class="permission-name add-link" data-text="dataplex.metadataFeeds.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.metadataFeeds.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.metadataJobs.cancel" class="permission-name add-link" data-text="dataplex.metadataJobs.cancel" tabindex="-1"><code dir="ltr" translate="no">dataplex.metadataJobs.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataJobOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.metadataJobs.create" class="permission-name add-link" data-text="dataplex.metadataJobs.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.metadataJobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataJobOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.metadataJobs.get" class="permission-name add-link" data-text="dataplex.metadataJobs.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.metadataJobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataJobOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobViewer">Dataplex Metadata Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.metadataJobs.list" class="permission-name add-link" data-text="dataplex.metadataJobs.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.metadataJobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataJobOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobViewer">Dataplex Metadata Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.operations.cancel" class="permission-name add-link" data-text="dataplex.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">dataplex.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.operations.delete" class="permission-name add-link" data-text="dataplex.operations.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.operations.get" class="permission-name add-link" data-text="dataplex.operations.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanCreator">Dataplex DataScan Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.encryptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedViewer">Dataplex Metadata Feed Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataJobOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobViewer">Dataplex Metadata Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.operations.list" class="permission-name add-link" data-text="dataplex.operations.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.encryptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.partitions.create" class="permission-name add-link" data-text="dataplex.partitions.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.partitions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.partitions.delete" class="permission-name add-link" data-text="dataplex.partitions.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.partitions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.partitions.get" class="permission-name add-link" data-text="dataplex.partitions.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.partitions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.partitions.list" class="permission-name add-link" data-text="dataplex.partitions.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.partitions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.partitions.update" class="permission-name add-link" data-text="dataplex.partitions.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.partitions.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.projects.search" class="permission-name add-link" data-text="dataplex.projects.search" tabindex="-1"><code dir="ltr" translate="no">dataplex.projects.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.metadataViewer">BigQuery Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.securityAdmin">BigQuery Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.searchAdmin">DataCatalog Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.searchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateCreator">Data Catalog TagTemplate Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateViewer</code> )</p>
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
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.tasks.cancel" class="permission-name add-link" data-text="dataplex.tasks.cancel" tabindex="-1"><code dir="ltr" translate="no">dataplex.tasks.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.tasks.create" class="permission-name add-link" data-text="dataplex.tasks.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.tasks.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.tasks.delete" class="permission-name add-link" data-text="dataplex.tasks.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.tasks.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.tasks.get" class="permission-name add-link" data-text="dataplex.tasks.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.tasks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.tasks.getIamPolicy" class="permission-name add-link" data-text="dataplex.tasks.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.tasks.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.tasks.list" class="permission-name add-link" data-text="dataplex.tasks.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.tasks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.tasks.run" class="permission-name add-link" data-text="dataplex.tasks.run" tabindex="-1"><code dir="ltr" translate="no">dataplex.tasks.run</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.tasks.setIamPolicy" class="permission-name add-link" data-text="dataplex.tasks.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.tasks.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.tasks.update" class="permission-name add-link" data-text="dataplex.tasks.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.tasks.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.zoneActions.list" class="permission-name add-link" data-text="dataplex.zoneActions.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.zoneActions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.zones.create" class="permission-name add-link" data-text="dataplex.zones.create" tabindex="-1"><code dir="ltr" translate="no">dataplex.zones.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.zones.delete" class="permission-name add-link" data-text="dataplex.zones.delete" tabindex="-1"><code dir="ltr" translate="no">dataplex.zones.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.zones.get" class="permission-name add-link" data-text="dataplex.zones.get" tabindex="-1"><code dir="ltr" translate="no">dataplex.zones.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.zones.getIamPolicy" class="permission-name add-link" data-text="dataplex.zones.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.zones.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
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
<td><h4 id="dataplex.zones.list" class="permission-name add-link" data-text="dataplex.zones.list" tabindex="-1"><code dir="ltr" translate="no">dataplex.zones.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex.zones.setIamPolicy" class="permission-name add-link" data-text="dataplex.zones.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataplex.zones.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataplex.zones.update" class="permission-name add-link" data-text="dataplex.zones.update" tabindex="-1"><code dir="ltr" translate="no">dataplex.zones.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.editor</code> )</p></td>
</tr>
</tbody>
</table>
