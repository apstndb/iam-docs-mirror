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
<td>Dataplex Administrator
<p>( <code>roles/ dataplex.admin</code> )</p>
<p>Full access to Dataplex Universal Catalog resources, except for catalog resources like entries and entry groups.</p></td>
<td><p><code>cloudasset. assets. analyzeIamPolicy</code></p>
<p><code>cloudasset. assets. searchAllIamPolicies</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>dataplex.assetActions.list</code></p>
<p><code>dataplex.assets.create</code></p>
<p><code>dataplex.assets.delete</code></p>
<p><code>dataplex.assets.get</code></p>
<p><code>dataplex.assets.getIamPolicy</code></p>
<p><code>dataplex.assets.list</code></p>
<p><code>dataplex.assets.setIamPolicy</code></p>
<p><code>dataplex.assets.update</code></p>
<p><code>dataplex.changeRequests.*</code></p>
<ul>
<li><code>dataplex. changeRequests. adminDelete</code></li>
<li><code>dataplex.changeRequests.delete</code></li>
<li><code>dataplex.changeRequests.get</code></li>
<li><code>dataplex. changeRequests. getIamPolicy</code></li>
<li><code>dataplex.changeRequests.list</code></li>
<li><code>dataplex. changeRequests. setIamPolicy</code></li>
<li><code>dataplex.changeRequests.update</code></li>
<li><code>dataplex.changeRequests.use</code></li>
</ul>
<p><code>dataplex.content.*</code></p>
<ul>
<li><code>dataplex.content.create</code></li>
<li><code>dataplex.content.delete</code></li>
<li><code>dataplex.content.get</code></li>
<li><code>dataplex.content.getIamPolicy</code></li>
<li><code>dataplex.content.list</code></li>
<li><code>dataplex.content.setIamPolicy</code></li>
<li><code>dataplex.content.update</code></li>
</ul>
<p><code>dataplex.dataAssets.*</code></p>
<ul>
<li><code>dataplex.dataAssets.create</code></li>
<li><code>dataplex.dataAssets.delete</code></li>
<li><code>dataplex.dataAssets.get</code></li>
<li><code>dataplex.dataAssets.list</code></li>
<li><code>dataplex.dataAssets.update</code></li>
</ul>
<p><code>dataplex. dataAttributeBindings.*</code></p>
<ul>
<li><code>dataplex. dataAttributeBindings. create</code></li>
<li><code>dataplex. dataAttributeBindings. delete</code></li>
<li><code>dataplex. dataAttributeBindings. get</code></li>
<li><code>dataplex. dataAttributeBindings. getIamPolicy</code></li>
<li><code>dataplex. dataAttributeBindings. list</code></li>
<li><code>dataplex. dataAttributeBindings. setIamPolicy</code></li>
<li><code>dataplex. dataAttributeBindings. update</code></li>
</ul>
<p><code>dataplex.dataAttributes.*</code></p>
<ul>
<li><code>dataplex.dataAttributes.bind</code></li>
<li><code>dataplex.dataAttributes.create</code></li>
<li><code>dataplex.dataAttributes.delete</code></li>
<li><code>dataplex.dataAttributes.get</code></li>
<li><code>dataplex. dataAttributes. getIamPolicy</code></li>
<li><code>dataplex.dataAttributes.list</code></li>
<li><code>dataplex. dataAttributes. setIamPolicy</code></li>
<li><code>dataplex.dataAttributes.update</code></li>
</ul>
<p><code>dataplex.dataDomainBindings.*</code></p>
<ul>
<li><code>dataplex. dataDomainBindings. create</code></li>
<li><code>dataplex. dataDomainBindings. delete</code></li>
<li><code>dataplex. dataDomainBindings. get</code></li>
<li><code>dataplex. dataDomainBindings. list</code></li>
</ul>
<p><code>dataplex.dataDomains.*</code></p>
<ul>
<li><code>dataplex.dataDomains.create</code></li>
<li><code>dataplex.dataDomains.delete</code></li>
<li><code>dataplex.dataDomains.discover</code></li>
<li><code>dataplex.dataDomains.get</code></li>
<li><code>dataplex. dataDomains. getIamPolicy</code></li>
<li><code>dataplex.dataDomains.list</code></li>
<li><code>dataplex. dataDomains. lookupEntry</code></li>
<li><code>dataplex. dataDomains. modifyEntry</code></li>
<li><code>dataplex. dataDomains. setIamPolicy</code></li>
<li><code>dataplex.dataDomains.update</code></li>
</ul>
<p><code>dataplex.dataProducts.*</code></p>
<ul>
<li><code>dataplex.dataProducts.approve</code></li>
<li><code>dataplex.dataProducts.create</code></li>
<li><code>dataplex.dataProducts.delete</code></li>
<li><code>dataplex.dataProducts.get</code></li>
<li><code>dataplex. dataProducts. getIamPolicy</code></li>
<li><code>dataplex.dataProducts.list</code></li>
<li><code>dataplex. dataProducts. setIamPolicy</code></li>
<li><code>dataplex.dataProducts.update</code></li>
</ul>
<p><code>dataplex.dataTaxonomies.*</code></p>
<ul>
<li><code>dataplex. dataTaxonomies. configureDataAccess</code></li>
<li><code>dataplex. dataTaxonomies. configureResourceAccess</code></li>
<li><code>dataplex.dataTaxonomies.create</code></li>
<li><code>dataplex.dataTaxonomies.delete</code></li>
<li><code>dataplex.dataTaxonomies.get</code></li>
<li><code>dataplex. dataTaxonomies. getIamPolicy</code></li>
<li><code>dataplex.dataTaxonomies.list</code></li>
<li><code>dataplex. dataTaxonomies. setIamPolicy</code></li>
<li><code>dataplex.dataTaxonomies.update</code></li>
</ul>
<p><code>dataplex.datascans.*</code></p>
<ul>
<li><code>dataplex.datascans.cancel</code></li>
<li><code>dataplex.datascans.create</code></li>
<li><code>dataplex.datascans.delete</code></li>
<li><code>dataplex.datascans.get</code></li>
<li><code>dataplex.datascans.getData</code></li>
<li><code>dataplex. datascans. getIamPolicy</code></li>
<li><code>dataplex.datascans.list</code></li>
<li><code>dataplex.datascans.run</code></li>
<li><code>dataplex. datascans. setIamPolicy</code></li>
<li><code>dataplex.datascans.update</code></li>
</ul>
<p><code>dataplex.entities.*</code></p>
<ul>
<li><code>dataplex.entities.create</code></li>
<li><code>dataplex.entities.delete</code></li>
<li><code>dataplex.entities.get</code></li>
<li><code>dataplex.entities.list</code></li>
<li><code>dataplex.entities.update</code></li>
</ul>
<p><code>dataplex.entries.link</code></p>
<p><code>dataplex. entryGroups. createTagBinding</code></p>
<p><code>dataplex. entryGroups. deleteTagBinding</code></p>
<p><code>dataplex.entryGroups.export</code></p>
<p><code>dataplex.entryGroups.import</code></p>
<p><code>dataplex. entryGroups. listEffectiveTags</code></p>
<p><code>dataplex. entryGroups. listTagBindings</code></p>
<p><code>dataplex. entryGroups. requestChanges</code></p>
<p><code>dataplex. entryGroups. useContextEntryLink</code></p>
<p><code>dataplex. entryGroups. useDefinitionEntryLink</code></p>
<p><code>dataplex. entryGroups. useRelatedEntryLink</code></p>
<p><code>dataplex. entryGroups. useSchemaJoinEntryLink</code></p>
<p><code>dataplex. entryGroups. useSynonymEntryLink</code></p>
<p><code>dataplex.entryLinks.*</code></p>
<ul>
<li><code>dataplex.entryLinks.create</code></li>
<li><code>dataplex.entryLinks.delete</code></li>
<li><code>dataplex.entryLinks.get</code></li>
<li><code>dataplex.entryLinks.reference</code></li>
<li><code>dataplex.entryLinks.update</code></li>
</ul>
<p><code>dataplex. entryTypes. createTagBinding</code></p>
<p><code>dataplex. entryTypes. deleteTagBinding</code></p>
<p><code>dataplex. entryTypes. listEffectiveTags</code></p>
<p><code>dataplex. entryTypes. listTagBindings</code></p>
<p><code>dataplex.environments.*</code></p>
<ul>
<li><code>dataplex.environments.create</code></li>
<li><code>dataplex.environments.delete</code></li>
<li><code>dataplex.environments.execute</code></li>
<li><code>dataplex.environments.get</code></li>
<li><code>dataplex. environments. getIamPolicy</code></li>
<li><code>dataplex.environments.list</code></li>
<li><code>dataplex. environments. setIamPolicy</code></li>
<li><code>dataplex.environments.update</code></li>
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
<p><code>dataplex.governanceRules.*</code></p>
<ul>
<li><code>dataplex. governanceRules. createTagBinding</code></li>
<li><code>dataplex. governanceRules. deleteTagBinding</code></li>
<li><code>dataplex. governanceRules. listEffectiveTags</code></li>
<li><code>dataplex. governanceRules. listTagBindings</code></li>
</ul>
<p><code>dataplex.lakeActions.list</code></p>
<p><code>dataplex.lakes.*</code></p>
<ul>
<li><code>dataplex.lakes.create</code></li>
<li><code>dataplex.lakes.delete</code></li>
<li><code>dataplex.lakes.get</code></li>
<li><code>dataplex.lakes.getIamPolicy</code></li>
<li><code>dataplex.lakes.list</code></li>
<li><code>dataplex.lakes.setIamPolicy</code></li>
<li><code>dataplex.lakes.update</code></li>
</ul>
<p><code>dataplex.locations.*</code></p>
<ul>
<li><code>dataplex.locations.get</code></li>
<li><code>dataplex.locations.list</code></li>
</ul>
<p><code>dataplex.metadataFeeds.*</code></p>
<ul>
<li><code>dataplex.metadataFeeds.create</code></li>
<li><code>dataplex.metadataFeeds.delete</code></li>
<li><code>dataplex.metadataFeeds.get</code></li>
<li><code>dataplex.metadataFeeds.list</code></li>
<li><code>dataplex.metadataFeeds.update</code></li>
</ul>
<p><code>dataplex.metadataJobs.*</code></p>
<ul>
<li><code>dataplex.metadataJobs.cancel</code></li>
<li><code>dataplex.metadataJobs.create</code></li>
<li><code>dataplex.metadataJobs.get</code></li>
<li><code>dataplex.metadataJobs.list</code></li>
</ul>
<p><code>dataplex.operations.*</code></p>
<ul>
<li><code>dataplex.operations.cancel</code></li>
<li><code>dataplex.operations.delete</code></li>
<li><code>dataplex.operations.get</code></li>
<li><code>dataplex.operations.list</code></li>
</ul>
<p><code>dataplex.partitions.*</code></p>
<ul>
<li><code>dataplex.partitions.create</code></li>
<li><code>dataplex.partitions.delete</code></li>
<li><code>dataplex.partitions.get</code></li>
<li><code>dataplex.partitions.list</code></li>
<li><code>dataplex.partitions.update</code></li>
</ul>
<p><code>dataplex.tasks.*</code></p>
<ul>
<li><code>dataplex.tasks.cancel</code></li>
<li><code>dataplex.tasks.create</code></li>
<li><code>dataplex.tasks.delete</code></li>
<li><code>dataplex.tasks.get</code></li>
<li><code>dataplex.tasks.getIamPolicy</code></li>
<li><code>dataplex.tasks.list</code></li>
<li><code>dataplex.tasks.run</code></li>
<li><code>dataplex.tasks.setIamPolicy</code></li>
<li><code>dataplex.tasks.update</code></li>
</ul>
<p><code>dataplex.zoneActions.list</code></p>
<p><code>dataplex.zones.*</code></p>
<ul>
<li><code>dataplex.zones.create</code></li>
<li><code>dataplex.zones.delete</code></li>
<li><code>dataplex.zones.get</code></li>
<li><code>dataplex.zones.getIamPolicy</code></li>
<li><code>dataplex.zones.list</code></li>
<li><code>dataplex.zones.setIamPolicy</code></li>
<li><code>dataplex.zones.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex DataScan Administrator
<p>( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p>Full access to DataScan resources.</p></td>
<td><p><code>dataplex.datascans.*</code></p>
<ul>
<li><code>dataplex.datascans.cancel</code></li>
<li><code>dataplex.datascans.create</code></li>
<li><code>dataplex.datascans.delete</code></li>
<li><code>dataplex.datascans.get</code></li>
<li><code>dataplex.datascans.getData</code></li>
<li><code>dataplex. datascans. getIamPolicy</code></li>
<li><code>dataplex.datascans.list</code></li>
<li><code>dataplex.datascans.run</code></li>
<li><code>dataplex. datascans. setIamPolicy</code></li>
<li><code>dataplex.datascans.update</code></li>
</ul>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.operations.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Editor
<p>( <code>roles/ dataplex.editor</code> )</p>
<p>Write access to Dataplex Universal Catalog resources, except for catalog resources like entries, entry groups, and glossaries.</p></td>
<td><p><code>cloudasset. assets. analyzeIamPolicy</code></p>
<p><code>dataplex.assetActions.list</code></p>
<p><code>dataplex.assets.create</code></p>
<p><code>dataplex.assets.delete</code></p>
<p><code>dataplex.assets.get</code></p>
<p><code>dataplex.assets.getIamPolicy</code></p>
<p><code>dataplex.assets.list</code></p>
<p><code>dataplex.assets.update</code></p>
<p><code>dataplex.content.delete</code></p>
<p><code>dataplex.content.get</code></p>
<p><code>dataplex.content.getIamPolicy</code></p>
<p><code>dataplex.content.list</code></p>
<p><code>dataplex.dataAssets.*</code></p>
<ul>
<li><code>dataplex.dataAssets.create</code></li>
<li><code>dataplex.dataAssets.delete</code></li>
<li><code>dataplex.dataAssets.get</code></li>
<li><code>dataplex.dataAssets.list</code></li>
<li><code>dataplex.dataAssets.update</code></li>
</ul>
<p><code>dataplex. dataAttributeBindings. create</code></p>
<p><code>dataplex. dataAttributeBindings. delete</code></p>
<p><code>dataplex. dataAttributeBindings. get</code></p>
<p><code>dataplex. dataAttributeBindings. getIamPolicy</code></p>
<p><code>dataplex. dataAttributeBindings. list</code></p>
<p><code>dataplex. dataAttributeBindings. update</code></p>
<p><code>dataplex.dataAttributes.bind</code></p>
<p><code>dataplex.dataAttributes.create</code></p>
<p><code>dataplex.dataAttributes.delete</code></p>
<p><code>dataplex.dataAttributes.get</code></p>
<p><code>dataplex. dataAttributes. getIamPolicy</code></p>
<p><code>dataplex.dataAttributes.list</code></p>
<p><code>dataplex.dataAttributes.update</code></p>
<p><code>dataplex.dataProducts.approve</code></p>
<p><code>dataplex.dataProducts.create</code></p>
<p><code>dataplex.dataProducts.delete</code></p>
<p><code>dataplex.dataProducts.get</code></p>
<p><code>dataplex. dataProducts. getIamPolicy</code></p>
<p><code>dataplex.dataProducts.list</code></p>
<p><code>dataplex.dataProducts.update</code></p>
<p><code>dataplex. dataTaxonomies. configureDataAccess</code></p>
<p><code>dataplex. dataTaxonomies. configureResourceAccess</code></p>
<p><code>dataplex.dataTaxonomies.create</code></p>
<p><code>dataplex.dataTaxonomies.delete</code></p>
<p><code>dataplex.dataTaxonomies.get</code></p>
<p><code>dataplex. dataTaxonomies. getIamPolicy</code></p>
<p><code>dataplex.dataTaxonomies.list</code></p>
<p><code>dataplex.dataTaxonomies.update</code></p>
<p><code>dataplex.datascans.cancel</code></p>
<p><code>dataplex.datascans.create</code></p>
<p><code>dataplex.datascans.delete</code></p>
<p><code>dataplex.datascans.get</code></p>
<p><code>dataplex. datascans. getIamPolicy</code></p>
<p><code>dataplex.datascans.list</code></p>
<p><code>dataplex.datascans.run</code></p>
<p><code>dataplex.datascans.update</code></p>
<p><code>dataplex.environments.create</code></p>
<p><code>dataplex.environments.delete</code></p>
<p><code>dataplex.environments.get</code></p>
<p><code>dataplex. environments. getIamPolicy</code></p>
<p><code>dataplex.environments.list</code></p>
<p><code>dataplex.environments.update</code></p>
<p><code>dataplex.lakeActions.list</code></p>
<p><code>dataplex.lakes.create</code></p>
<p><code>dataplex.lakes.delete</code></p>
<p><code>dataplex.lakes.get</code></p>
<p><code>dataplex.lakes.getIamPolicy</code></p>
<p><code>dataplex.lakes.list</code></p>
<p><code>dataplex.lakes.update</code></p>
<p><code>dataplex.operations.*</code></p>
<ul>
<li><code>dataplex.operations.cancel</code></li>
<li><code>dataplex.operations.delete</code></li>
<li><code>dataplex.operations.get</code></li>
<li><code>dataplex.operations.list</code></li>
</ul>
<p><code>dataplex.tasks.cancel</code></p>
<p><code>dataplex.tasks.create</code></p>
<p><code>dataplex.tasks.delete</code></p>
<p><code>dataplex.tasks.get</code></p>
<p><code>dataplex.tasks.getIamPolicy</code></p>
<p><code>dataplex.tasks.list</code></p>
<p><code>dataplex.tasks.run</code></p>
<p><code>dataplex.tasks.update</code></p>
<p><code>dataplex.zoneActions.list</code></p>
<p><code>dataplex.zones.create</code></p>
<p><code>dataplex.zones.delete</code></p>
<p><code>dataplex.zones.get</code></p>
<p><code>dataplex.zones.getIamPolicy</code></p>
<p><code>dataplex.zones.list</code></p>
<p><code>dataplex.zones.update</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Viewer
<p>( <code>roles/ dataplex.viewer</code> )</p>
<p>Read access to Dataplex Universal Catalog resources, except for catalog resources like entries, entry groups, and glossaries.</p></td>
<td><p><code>cloudasset. assets. analyzeIamPolicy</code></p>
<p><code>dataplex.assetActions.list</code></p>
<p><code>dataplex.assets.get</code></p>
<p><code>dataplex.assets.getIamPolicy</code></p>
<p><code>dataplex.assets.list</code></p>
<p><code>dataplex.content.get</code></p>
<p><code>dataplex.content.getIamPolicy</code></p>
<p><code>dataplex.content.list</code></p>
<p><code>dataplex.dataAssets.get</code></p>
<p><code>dataplex.dataAssets.list</code></p>
<p><code>dataplex. dataAttributeBindings. get</code></p>
<p><code>dataplex. dataAttributeBindings. getIamPolicy</code></p>
<p><code>dataplex. dataAttributeBindings. list</code></p>
<p><code>dataplex.dataAttributes.get</code></p>
<p><code>dataplex. dataAttributes. getIamPolicy</code></p>
<p><code>dataplex.dataAttributes.list</code></p>
<p><code>dataplex.dataProducts.get</code></p>
<p><code>dataplex. dataProducts. getIamPolicy</code></p>
<p><code>dataplex.dataProducts.list</code></p>
<p><code>dataplex.dataTaxonomies.get</code></p>
<p><code>dataplex. dataTaxonomies. getIamPolicy</code></p>
<p><code>dataplex.dataTaxonomies.list</code></p>
<p><code>dataplex.datascans.get</code></p>
<p><code>dataplex. datascans. getIamPolicy</code></p>
<p><code>dataplex.datascans.list</code></p>
<p><code>dataplex.environments.get</code></p>
<p><code>dataplex. environments. getIamPolicy</code></p>
<p><code>dataplex.environments.list</code></p>
<p><code>dataplex.lakeActions.list</code></p>
<p><code>dataplex.lakes.get</code></p>
<p><code>dataplex.lakes.getIamPolicy</code></p>
<p><code>dataplex.lakes.list</code></p>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.operations.list</code></p>
<p><code>dataplex.tasks.get</code></p>
<p><code>dataplex.tasks.getIamPolicy</code></p>
<p><code>dataplex.tasks.list</code></p>
<p><code>dataplex.zoneActions.list</code></p>
<p><code>dataplex.zones.get</code></p>
<p><code>dataplex.zones.getIamPolicy</code></p>
<p><code>dataplex.zones.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Aspect Type Owner
<p>( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p>Grants access to creating and managing Aspect Types. Does not give the right to create/modify Entries.</p></td>
<td><p><code>datacatalog. migrationConfig. get</code></p>
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
<td>Dataplex Aspect Type User
<p>( <code>roles/ dataplex.aspectTypeUser</code> )</p>
<p>Grants access to use Aspect Types to create/modify Entries with the corresponding aspects.</p></td>
<td><p><code>datacatalog. migrationConfig. get</code></p>
<p><code>dataplex.aspectTypes.get</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex.aspectTypes.use</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Binding Administrator
<p>( <code>roles/ dataplex.bindingAdmin</code> )</p>
<p>Full access on DataAttribute Binding resources.</p></td>
<td><p><code>dataplex. dataAttributeBindings.*</code></p>
<ul>
<li><code>dataplex. dataAttributeBindings. create</code></li>
<li><code>dataplex. dataAttributeBindings. delete</code></li>
<li><code>dataplex. dataAttributeBindings. get</code></li>
<li><code>dataplex. dataAttributeBindings. getIamPolicy</code></li>
<li><code>dataplex. dataAttributeBindings. list</code></li>
<li><code>dataplex. dataAttributeBindings. setIamPolicy</code></li>
<li><code>dataplex. dataAttributeBindings. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Dataplex Catalog Admin
<p>( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p>Full access to catalog resources, including entries, entry groups, and glossaries.</p></td>
<td><p><code>datacatalog. migrationConfig. get</code></p>
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
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Catalog Editor
<p>( <code>roles/ dataplex.catalogEditor</code> )</p>
<p>Write access to catalog resources, including entries, entry groups, and glossaries. Cannot set IAM policies on resources.</p></td>
<td><p><code>datacatalog. migrationConfig. get</code></p>
<p><code>dataplex.aspectTypes.create</code></p>
<p><code>dataplex.aspectTypes.delete</code></p>
<p><code>dataplex.aspectTypes.get</code></p>
<p><code>dataplex. aspectTypes. getIamPolicy</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex.aspectTypes.update</code></p>
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
<p><code>dataplex.entryGroups.create</code></p>
<p><code>dataplex.entryGroups.delete</code></p>
<p><code>dataplex.entryGroups.get</code></p>
<p><code>dataplex. entryGroups. getIamPolicy</code></p>
<p><code>dataplex.entryGroups.list</code></p>
<p><code>dataplex. entryGroups. listEffectiveTags</code></p>
<p><code>dataplex. entryGroups. listTagBindings</code></p>
<p><code>dataplex.entryGroups.update</code></p>
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
<p><code>dataplex.entryLinkTypes.create</code></p>
<p><code>dataplex.entryLinkTypes.delete</code></p>
<p><code>dataplex.entryLinkTypes.get</code></p>
<p><code>dataplex. entryLinkTypes. getIamPolicy</code></p>
<p><code>dataplex.entryLinkTypes.list</code></p>
<p><code>dataplex.entryLinkTypes.update</code></p>
<p><code>dataplex.entryLinkTypes.use</code></p>
<p><code>dataplex.entryLinks.create</code></p>
<p><code>dataplex.entryLinks.delete</code></p>
<p><code>dataplex.entryLinks.get</code></p>
<p><code>dataplex.entryLinks.update</code></p>
<p><code>dataplex.entryTypes.create</code></p>
<p><code>dataplex.entryTypes.delete</code></p>
<p><code>dataplex.entryTypes.get</code></p>
<p><code>dataplex. entryTypes. getIamPolicy</code></p>
<p><code>dataplex.entryTypes.list</code></p>
<p><code>dataplex. entryTypes. listEffectiveTags</code></p>
<p><code>dataplex. entryTypes. listTagBindings</code></p>
<p><code>dataplex.entryTypes.update</code></p>
<p><code>dataplex.entryTypes.use</code></p>
<p><code>dataplex.glossaries.create</code></p>
<p><code>dataplex.glossaries.delete</code></p>
<p><code>dataplex.glossaries.get</code></p>
<p><code>dataplex. glossaries. getIamPolicy</code></p>
<p><code>dataplex.glossaries.list</code></p>
<p><code>dataplex.glossaries.update</code></p>
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
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Catalog Viewer
<p>( <code>roles/ dataplex.catalogViewer</code> )</p>
<p>Read access to catalog resources, including entries, entry groups, and glossaries. Can view IAM policies on catalog resources.</p></td>
<td><p><code>datacatalog. migrationConfig. get</code></p>
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
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Change Request Owner <sup>Beta</sup>
<p>( <code>roles/ dataplex.changeRequestOwner</code> )</p>
<p>Grants Change Request creator necessary permissions on a created ChangeRequest instance.</p></td>
<td><p><code>dataplex.changeRequests.delete</code></p>
<p><code>dataplex.changeRequests.get</code></p>
<p><code>dataplex.changeRequests.update</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Data Domain Admin <sup>Beta</sup>
<p>( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p>Allows full management of the Data Domain and its bindings.</p></td>
<td><p><code>dataplex.dataDomainBindings.*</code></p>
<ul>
<li><code>dataplex. dataDomainBindings. create</code></li>
<li><code>dataplex. dataDomainBindings. delete</code></li>
<li><code>dataplex. dataDomainBindings. get</code></li>
<li><code>dataplex. dataDomainBindings. list</code></li>
</ul>
<p><code>dataplex.dataDomains.create</code></p>
<p><code>dataplex.dataDomains.delete</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.dataDomains.get</code></p>
<p><code>dataplex. dataDomains. getIamPolicy</code></p>
<p><code>dataplex.dataDomains.list</code></p>
<p><code>dataplex. dataDomains. lookupEntry</code></p>
<p><code>dataplex. dataDomains. setIamPolicy</code></p>
<p><code>dataplex.dataDomains.update</code></p>
<p><code>dataplex.operations.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Data Domain Configuration Editor <sup>Beta</sup>
<p>( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p>Allows updating the Data Domain as well as full management of its bindings.</p></td>
<td><p><code>dataplex.dataDomainBindings.*</code></p>
<ul>
<li><code>dataplex. dataDomainBindings. create</code></li>
<li><code>dataplex. dataDomainBindings. delete</code></li>
<li><code>dataplex. dataDomainBindings. get</code></li>
<li><code>dataplex. dataDomainBindings. list</code></li>
</ul>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.dataDomains.get</code></p>
<p><code>dataplex. dataDomains. getIamPolicy</code></p>
<p><code>dataplex.dataDomains.list</code></p>
<p><code>dataplex. dataDomains. lookupEntry</code></p>
<p><code>dataplex.dataDomains.update</code></p>
<p><code>dataplex.operations.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Data Domain Entry Reader <sup>Beta</sup>
<p>( <code>roles/ dataplex.dataDomainEntryReader</code> )</p>
<p>Allows discovering and viewing the Data Domain, its subdomains, and metadata of all its resources.</p></td>
<td><p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.dataDomains.get</code></p>
<p><code>dataplex.dataDomains.list</code></p>
<p><code>dataplex. dataDomains. lookupEntry</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Data Domain Configuration Viewer <sup>Beta</sup>
<p>( <code>roles/ dataplex.dataDomainViewer</code> )</p>
<p>Allows viewing the configuration of the Data Domain and its bindings.</p></td>
<td><p><code>dataplex. dataDomainBindings. get</code></p>
<p><code>dataplex. dataDomainBindings. list</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.dataDomains.get</code></p>
<p><code>dataplex. dataDomains. getIamPolicy</code></p>
<p><code>dataplex.dataDomains.list</code></p>
<p><code>dataplex. dataDomains. lookupEntry</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Data Owner
<p>( <code>roles/ dataplex.dataOwner</code> )</p>
<p>Owner access to data. To be granted to Dataplex Universal Catalog resources Lake, Zone or Asset only.</p></td>
<td><p><code>dataplex.assets.ownData</code></p>
<p><code>dataplex.assets.readData</code></p>
<p><code>dataplex.assets.writeData</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Data Products Admin
<p>( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p>Full access to Data Products.</p></td>
<td><p><code>dataplex.dataAssets.*</code></p>
<ul>
<li><code>dataplex.dataAssets.create</code></li>
<li><code>dataplex.dataAssets.delete</code></li>
<li><code>dataplex.dataAssets.get</code></li>
<li><code>dataplex.dataAssets.list</code></li>
<li><code>dataplex.dataAssets.update</code></li>
</ul>
<p><code>dataplex.dataProducts.*</code></p>
<ul>
<li><code>dataplex.dataProducts.approve</code></li>
<li><code>dataplex.dataProducts.create</code></li>
<li><code>dataplex.dataProducts.delete</code></li>
<li><code>dataplex.dataProducts.get</code></li>
<li><code>dataplex. dataProducts. getIamPolicy</code></li>
<li><code>dataplex.dataProducts.list</code></li>
<li><code>dataplex. dataProducts. setIamPolicy</code></li>
<li><code>dataplex.dataProducts.update</code></li>
</ul>
<p><code>dataplex.operations.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Data Products Consumer
<p>( <code>roles/ dataplex.dataProductsConsumer</code> )</p>
<p>Restricted read access, intended for consumers of Data Products.</p></td>
<td><p><code>dataplex.dataAssets.get</code></p>
<p><code>dataplex.dataAssets.list</code></p>
<p><code>dataplex.dataProducts.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Data Products Editor
<p>( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p>Write access to Data Products.</p></td>
<td><p><code>dataplex.dataAssets.*</code></p>
<ul>
<li><code>dataplex.dataAssets.create</code></li>
<li><code>dataplex.dataAssets.delete</code></li>
<li><code>dataplex.dataAssets.get</code></li>
<li><code>dataplex.dataAssets.list</code></li>
<li><code>dataplex.dataAssets.update</code></li>
</ul>
<p><code>dataplex.dataProducts.approve</code></p>
<p><code>dataplex.dataProducts.create</code></p>
<p><code>dataplex.dataProducts.delete</code></p>
<p><code>dataplex.dataProducts.get</code></p>
<p><code>dataplex. dataProducts. getIamPolicy</code></p>
<p><code>dataplex.dataProducts.list</code></p>
<p><code>dataplex.dataProducts.update</code></p>
<p><code>dataplex.operations.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Data Products Viewer
<p>( <code>roles/ dataplex.dataProductsViewer</code> )</p>
<p>Read access to Data Products.</p></td>
<td><p><code>dataplex.dataAssets.get</code></p>
<p><code>dataplex.dataAssets.list</code></p>
<p><code>dataplex.dataProducts.get</code></p>
<p><code>dataplex. dataProducts. getIamPolicy</code></p>
<p><code>dataplex.dataProducts.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Data Reader
<p>( <code>roles/ dataplex.dataReader</code> )</p>
<p>Read only access to data. To be granted to Dataplex Universal Catalog resources Lake, Zone or Asset only.</p></td>
<td><p><code>dataplex.assets.readData</code></p></td>
</tr>
<tr class="even">
<td>Dataplex DataScan Creator
<p>( <code>roles/ dataplex.dataScanCreator</code> )</p>
<p>Access to create new DataScan resources.</p></td>
<td><p><code>dataplex.datascans.create</code></p>
<p><code>dataplex.datascans.get</code></p>
<p><code>dataplex.datascans.list</code></p>
<p><code>dataplex.operations.get</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex DataScan DataViewer
<p>( <code>roles/ dataplex.dataScanDataViewer</code> )</p>
<p>Read access to DataScan resources, including the results.</p></td>
<td><p><code>dataplex.datascans.get</code></p>
<p><code>dataplex.datascans.getData</code></p>
<p><code>dataplex. datascans. getIamPolicy</code></p>
<p><code>dataplex.datascans.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex DataScan Editor
<p>( <code>roles/ dataplex.dataScanEditor</code> )</p>
<p>Write access to DataScan resources.</p></td>
<td><p><code>dataplex.datascans.cancel</code></p>
<p><code>dataplex.datascans.create</code></p>
<p><code>dataplex.datascans.delete</code></p>
<p><code>dataplex.datascans.get</code></p>
<p><code>dataplex.datascans.getData</code></p>
<p><code>dataplex. datascans. getIamPolicy</code></p>
<p><code>dataplex.datascans.list</code></p>
<p><code>dataplex.datascans.run</code></p>
<p><code>dataplex.datascans.update</code></p>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.operations.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex DataScan Viewer
<p>( <code>roles/ dataplex.dataScanViewer</code> )</p>
<p>Read access to DataScan resources, excluding the results.</p></td>
<td><p><code>dataplex.datascans.get</code></p>
<p><code>dataplex. datascans. getIamPolicy</code></p>
<p><code>dataplex.datascans.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Data Writer
<p>( <code>roles/ dataplex.dataWriter</code> )</p>
<p>Write access to data. To be granted to Dataplex Universal Catalog resources Lake, Zone or Asset only.</p></td>
<td><p><code>dataplex.assets.writeData</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Developer
<p>( <code>roles/ dataplex.developer</code> )</p>
<p>Allows running data analytics workloads in a lake.</p></td>
<td><p><code>dataplex.content.*</code></p>
<ul>
<li><code>dataplex.content.create</code></li>
<li><code>dataplex.content.delete</code></li>
<li><code>dataplex.content.get</code></li>
<li><code>dataplex.content.getIamPolicy</code></li>
<li><code>dataplex.content.list</code></li>
<li><code>dataplex.content.setIamPolicy</code></li>
<li><code>dataplex.content.update</code></li>
</ul>
<p><code>dataplex.environments.execute</code></p>
<p><code>dataplex.environments.get</code></p>
<p><code>dataplex.environments.list</code></p>
<p><code>dataplex.tasks.cancel</code></p>
<p><code>dataplex.tasks.create</code></p>
<p><code>dataplex.tasks.delete</code></p>
<p><code>dataplex.tasks.get</code></p>
<p><code>dataplex.tasks.list</code></p>
<p><code>dataplex.tasks.run</code></p>
<p><code>dataplex.tasks.update</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Encryption Admin
<p>( <code>roles/ dataplex.encryptionAdmin</code> )</p>
<p>Gives user permissions to manage encryption configurations.</p></td>
<td><p><code>dataplex.encryptionConfig.*</code></p>
<ul>
<li><code>dataplex. encryptionConfig. create</code></li>
<li><code>dataplex. encryptionConfig. delete</code></li>
<li><code>dataplex.encryptionConfig.get</code></li>
<li><code>dataplex.encryptionConfig.list</code></li>
<li><code>dataplex. encryptionConfig. update</code></li>
</ul>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.operations.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Entry Group Exporter
<p>( <code>roles/ dataplex.entryGroupExporter</code> )</p>
<p>Grants access to export this entry group for Metadata Job processing.</p></td>
<td><p><code>dataplex.entryGroups.export</code></p>
<p><code>dataplex.entryGroups.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Entry Group Importer
<p>( <code>roles/ dataplex.entryGroupImporter</code> )</p>
<p>Grants access to import this entry group for Metadata Job processing.</p></td>
<td><p><code>dataplex.entryGroups.get</code></p>
<p><code>dataplex.entryGroups.import</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Entry Group Owner
<p>( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p>Owns Entry Groups and Entries inside of them.</p></td>
<td><p><code>datacatalog. migrationConfig. get</code></p>
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
<tr class="even">
<td>Dataplex Entry Link Type Owner
<p>( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p>Grants access to creating and managing Entry Link Types. Does not give the right to create/modify Entry Links.</p></td>
<td><p><code>dataplex.dataDomains.discover</code></p>
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
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Entry Link Type User
<p>( <code>roles/ dataplex.entryLinkTypeUser</code> )</p>
<p>Grants access to use Entry Link Types to create EntryLinks of those types.</p></td>
<td><p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.entryLinkTypes.get</code></p>
<p><code>dataplex.entryLinkTypes.list</code></p>
<p><code>dataplex.entryLinkTypes.use</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Entry and EntryLink Owner
<p>( <code>roles/ dataplex.entryOwner</code> )</p>
<p>Owns Metadata Entries and EntryLinks.</p></td>
<td><p><code>datacatalog. migrationConfig. get</code></p>
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
<tr class="odd">
<td>Dataplex Entry Type Owner
<p>( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p>Grants access to creating and managing Entry Types. Does not give the right to create/modify Entries.</p></td>
<td><p><code>datacatalog. migrationConfig. get</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
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
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Entry Type User
<p>( <code>roles/ dataplex.entryTypeUser</code> )</p>
<p>Grants access to use Entry Types to create/modify Entries of those types.</p></td>
<td><p><code>datacatalog. migrationConfig. get</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.entryTypes.get</code></p>
<p><code>dataplex.entryTypes.list</code></p>
<p><code>dataplex. entryTypes. listEffectiveTags</code></p>
<p><code>dataplex. entryTypes. listTagBindings</code></p>
<p><code>dataplex.entryTypes.use</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Metadata Feed Owner
<p>( <code>roles/ dataplex.metadataFeedOwner</code> )</p>
<p>Grants access to creating and managing Metadata Feeds. Does not give the right to create/modify Entry Groups.</p></td>
<td><p><code>dataplex.metadataFeeds.*</code></p>
<ul>
<li><code>dataplex.metadataFeeds.create</code></li>
<li><code>dataplex.metadataFeeds.delete</code></li>
<li><code>dataplex.metadataFeeds.get</code></li>
<li><code>dataplex.metadataFeeds.list</code></li>
<li><code>dataplex.metadataFeeds.update</code></li>
</ul>
<p><code>dataplex.operations.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Metadata Feed Viewer
<p>( <code>roles/ dataplex.metadataFeedViewer</code> )</p>
<p>Read access to Metadata Feed resources.</p></td>
<td><p><code>dataplex.metadataFeeds.get</code></p>
<p><code>dataplex.metadataFeeds.list</code></p>
<p><code>dataplex.operations.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Metadata Job Owner
<p>( <code>roles/ dataplex.metadataJobOwner</code> )</p>
<p>Grants access to creating and managing Metadata Jobs. Does not give the right to create/modify Entry Groups.</p></td>
<td><p><code>dataplex.metadataJobs.*</code></p>
<ul>
<li><code>dataplex.metadataJobs.cancel</code></li>
<li><code>dataplex.metadataJobs.create</code></li>
<li><code>dataplex.metadataJobs.get</code></li>
<li><code>dataplex.metadataJobs.list</code></li>
</ul>
<p><code>dataplex.operations.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Metadata Job Viewer
<p>( <code>roles/ dataplex.metadataJobViewer</code> )</p>
<p>Read access to Metadata Job resources.</p></td>
<td><p><code>dataplex.metadataJobs.get</code></p>
<p><code>dataplex.metadataJobs.list</code></p>
<p><code>dataplex.operations.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Metadata Reader
<p>( <code>roles/ dataplex.metadataReader</code> )</p>
<p>Read only access to metadata within table and fileset entities and partitions.</p></td>
<td><p><code>dataplex.assets.get</code></p>
<p><code>dataplex.assets.list</code></p>
<p><code>dataplex.entities.get</code></p>
<p><code>dataplex.entities.list</code></p>
<p><code>dataplex.partitions.get</code></p>
<p><code>dataplex.partitions.list</code></p>
<p><code>dataplex.zones.get</code></p>
<p><code>dataplex.zones.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Metadata Writer
<p>( <code>roles/ dataplex.metadataWriter</code> )</p>
<p>Write and read access to metadata within table and fileset entities and partitions.</p></td>
<td><p><code>dataplex.assets.get</code></p>
<p><code>dataplex.assets.list</code></p>
<p><code>dataplex.entities.*</code></p>
<ul>
<li><code>dataplex.entities.create</code></li>
<li><code>dataplex.entities.delete</code></li>
<li><code>dataplex.entities.get</code></li>
<li><code>dataplex.entities.list</code></li>
<li><code>dataplex.entities.update</code></li>
</ul>
<p><code>dataplex.partitions.*</code></p>
<ul>
<li><code>dataplex.partitions.create</code></li>
<li><code>dataplex.partitions.delete</code></li>
<li><code>dataplex.partitions.get</code></li>
<li><code>dataplex.partitions.list</code></li>
<li><code>dataplex.partitions.update</code></li>
</ul>
<p><code>dataplex.zones.get</code></p>
<p><code>dataplex.zones.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Security Administrator
<p>( <code>roles/ dataplex.securityAdmin</code> )</p>
<p>Permissions configure ResourceAccess and DataAccess Specs on Data Attributes.</p></td>
<td><p><code>dataplex. dataTaxonomies. configureDataAccess</code></p>
<p><code>dataplex. dataTaxonomies. configureResourceAccess</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Storage Data Owner
<p>( <code>roles/ dataplex.storageDataOwner</code> )</p>
<p>Owner access to data. Should not be used directly. This role is granted by Dataplex to managed resources like Cloud Storage buckets, BigQuery datasets etc.</p></td>
<td><p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.models.create</code></p>
<p><code>bigquery.models.delete</code></p>
<p><code>bigquery.models.export</code></p>
<p><code>bigquery.models.getData</code></p>
<p><code>bigquery.models.getMetadata</code></p>
<p><code>bigquery.models.list</code></p>
<p><code>bigquery.models.updateData</code></p>
<p><code>bigquery.models.updateMetadata</code></p>
<p><code>bigquery.routines.create</code></p>
<p><code>bigquery.routines.delete</code></p>
<p><code>bigquery.routines.get</code></p>
<p><code>bigquery.routines.list</code></p>
<p><code>bigquery.routines.update</code></p>
<p><code>bigquery.tables.create</code></p>
<p><code>bigquery.tables.createSnapshot</code></p>
<p><code>bigquery.tables.delete</code></p>
<p><code>bigquery.tables.deleteSnapshot</code></p>
<p><code>bigquery.tables.export</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.getData</code></p>
<p><code>bigquery.tables.list</code></p>
<p><code>bigquery. tables. restoreSnapshot</code></p>
<p><code>bigquery.tables.update</code></p>
<p><code>bigquery.tables.updateData</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Storage Data Reader
<p>( <code>roles/ dataplex.storageDataReader</code> )</p>
<p>Read only access to data. Should not be used directly. This role is granted by Dataplex to managed resources like Cloud Storage buckets, BigQuery datasets etc.</p></td>
<td><p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.models.export</code></p>
<p><code>bigquery.models.getData</code></p>
<p><code>bigquery.models.getMetadata</code></p>
<p><code>bigquery.models.list</code></p>
<p><code>bigquery.routines.get</code></p>
<p><code>bigquery.routines.list</code></p>
<p><code>bigquery.tables.export</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.getData</code></p>
<p><code>bigquery.tables.list</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Storage Data Writer
<p>( <code>roles/ dataplex.storageDataWriter</code> )</p>
<p>Write access to data. Should not be used directly. This role is granted by Dataplex to managed resources like Cloud Storage buckets, BigQuery datasets etc.</p></td>
<td><p><code>bigquery.tables.updateData</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.update</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Taxonomy Administrator
<p>( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p>Full access to DataTaxonomy, DataAttribute resources.</p></td>
<td><p><code>dataplex.dataAttributes.*</code></p>
<ul>
<li><code>dataplex.dataAttributes.bind</code></li>
<li><code>dataplex.dataAttributes.create</code></li>
<li><code>dataplex.dataAttributes.delete</code></li>
<li><code>dataplex.dataAttributes.get</code></li>
<li><code>dataplex. dataAttributes. getIamPolicy</code></li>
<li><code>dataplex.dataAttributes.list</code></li>
<li><code>dataplex. dataAttributes. setIamPolicy</code></li>
<li><code>dataplex.dataAttributes.update</code></li>
</ul>
<p><code>dataplex.dataTaxonomies.create</code></p>
<p><code>dataplex.dataTaxonomies.delete</code></p>
<p><code>dataplex.dataTaxonomies.get</code></p>
<p><code>dataplex. dataTaxonomies. getIamPolicy</code></p>
<p><code>dataplex.dataTaxonomies.list</code></p>
<p><code>dataplex. dataTaxonomies. setIamPolicy</code></p>
<p><code>dataplex.dataTaxonomies.update</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Taxonomy Viewer
<p>( <code>roles/ dataplex.taxonomyViewer</code> )</p>
<p>Read access on DataTaxonomy, DataAttribute resources.</p></td>
<td><p><code>dataplex.dataAttributes.get</code></p>
<p><code>dataplex. dataAttributes. getIamPolicy</code></p>
<p><code>dataplex.dataAttributes.list</code></p>
<p><code>dataplex.dataTaxonomies.get</code></p>
<p><code>dataplex. dataTaxonomies. getIamPolicy</code></p>
<p><code>dataplex.dataTaxonomies.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Workflow Admin <sup>Beta</sup>
<p>( <code>roles/ dataplex.workflowAdmin</code> )</p>
<p>Full access to Change Requests in Approval Workflows.</p></td>
<td><p><code>dataplex. changeRequests. adminDelete</code></p>
<p><code>dataplex.changeRequests.delete</code></p>
<p><code>dataplex.changeRequests.get</code></p>
<p><code>dataplex.changeRequests.list</code></p>
<p><code>dataplex.changeRequests.use</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Workflow Approver <sup>Beta</sup>
<p>( <code>roles/ dataplex.workflowApprover</code> )</p>
<p>Access to approve, reject, or revoke Change Requests in Approval Workflows.</p></td>
<td><p><code>dataplex.changeRequests.get</code></p>
<p><code>dataplex.changeRequests.list</code></p>
<p><code>dataplex.changeRequests.use</code></p></td>
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
<td>Dataplex Discovery BigLake Publishing Service Agent
<p>( <code>roles/ dataplex.discoveryBigLakePublishingServiceAgent</code> )</p>
<p>Gives the Dataplex Discovery Service Agent permissions to use bigquery connection.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>bigquery.connections.delegate</code></p>
<p><code>bigquery.connections.use</code></p></td>
</tr>
<tr class="even">
<td>Dataplex Discovery Publishing Service Agent
<p>( <code>roles/ dataplex.discoveryPublishingServiceAgent</code> )</p>
<p>Gives the Dataplex Discovery Service Agent dataset create and get permissions.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>bigquery.datasets.create</code></p>
<p><code>bigquery.datasets.get</code></p></td>
</tr>
<tr class="odd">
<td>Dataplex Discovery Service Agent
<p>( <code>roles/ dataplex.discoveryServiceAgent</code> )</p>
<p>Gives the Dataplex Discovery Service Agent bucket read permissions.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>storage.buckets.get</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud Dataplex Service Agent
<p>( <code>roles/ dataplex.serviceAgent</code> )</p>
<p>Gives the Dataplex service account access to project resources. This access will be used in data discovery, data management and data workload management.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>biglake.catalogs.get</code></p>
<p><code>biglake.namespaces.get</code></p>
<p><code>biglake.tables.get</code></p>
<p><code>biglake.tables.getData</code></p>
<p><code>biglake.tables.list</code></p>
<p><code>bigquery.bireservations.*</code></p>
<ul>
<li><code>bigquery.bireservations.get</code></li>
<li><code>bigquery.bireservations.update</code></li>
</ul>
<p><code>bigquery.capacityCommitments.*</code></p>
<ul>
<li><code>bigquery. capacityCommitments. create</code></li>
<li><code>bigquery. capacityCommitments. delete</code></li>
<li><code>bigquery. capacityCommitments. get</code></li>
<li><code>bigquery. capacityCommitments. list</code></li>
<li><code>bigquery. capacityCommitments. update</code></li>
</ul>
<p><code>bigquery.config.*</code></p>
<ul>
<li><code>bigquery.config.get</code></li>
<li><code>bigquery.config.update</code></li>
</ul>
<p><code>bigquery.connections.*</code></p>
<ul>
<li><code>bigquery.connections.create</code></li>
<li><code>bigquery.connections.delegate</code></li>
<li><code>bigquery.connections.delete</code></li>
<li><code>bigquery.connections.get</code></li>
<li><code>bigquery. connections. getIamPolicy</code></li>
<li><code>bigquery.connections.list</code></li>
<li><code>bigquery. connections. setIamPolicy</code></li>
<li><code>bigquery.connections.update</code></li>
<li><code>bigquery.connections.updateTag</code></li>
<li><code>bigquery.connections.use</code></li>
</ul>
<p><code>bigquery.dataPolicies.attach</code></p>
<p><code>bigquery.dataPolicies.create</code></p>
<p><code>bigquery.dataPolicies.delete</code></p>
<p><code>bigquery.dataPolicies.get</code></p>
<p><code>bigquery. dataPolicies. getIamPolicy</code></p>
<p><code>bigquery.dataPolicies.list</code></p>
<p><code>bigquery. dataPolicies. setIamPolicy</code></p>
<p><code>bigquery.dataPolicies.update</code></p>
<p><code>bigquery.datasets.*</code></p>
<ul>
<li><code>bigquery.datasets.create</code></li>
<li><code>bigquery. datasets. createTagBinding</code></li>
<li><code>bigquery.datasets.delete</code></li>
<li><code>bigquery. datasets. deleteTagBinding</code></li>
<li><code>bigquery.datasets.get</code></li>
<li><code>bigquery.datasets.getIamPolicy</code></li>
<li><code>bigquery.datasets.link</code></li>
<li><code>bigquery. datasets. listEffectiveTags</code></li>
<li><code>bigquery. datasets. listSharedDatasetUsage</code></li>
<li><code>bigquery. datasets. listTagBindings</code></li>
<li><code>bigquery.datasets.setIamPolicy</code></li>
<li><code>bigquery.datasets.update</code></li>
<li><code>bigquery.datasets.updateTag</code></li>
</ul>
<p><code>bigquery.jobs.*</code></p>
<ul>
<li><code>bigquery.jobs.create</code></li>
<li><code>bigquery. jobs. createGlobalQuery</code></li>
<li><code>bigquery.jobs.delete</code></li>
<li><code>bigquery.jobs.get</code></li>
<li><code>bigquery.jobs.list</code></li>
<li><code>bigquery.jobs.listAll</code></li>
<li><code>bigquery. jobs. listExecutionMetadata</code></li>
<li><code>bigquery.jobs.update</code></li>
</ul>
<p><code>bigquery.models.*</code></p>
<ul>
<li><code>bigquery.models.create</code></li>
<li><code>bigquery.models.delete</code></li>
<li><code>bigquery.models.export</code></li>
<li><code>bigquery.models.getData</code></li>
<li><code>bigquery.models.getMetadata</code></li>
<li><code>bigquery.models.list</code></li>
<li><code>bigquery.models.updateData</code></li>
<li><code>bigquery.models.updateMetadata</code></li>
<li><code>bigquery.models.updateTag</code></li>
</ul>
<p><code>bigquery.objectRefs.*</code></p>
<ul>
<li><code>bigquery.objectRefs.read</code></li>
<li><code>bigquery.objectRefs.write</code></li>
</ul>
<p><code>bigquery.propertyGraphs.*</code></p>
<ul>
<li><code>bigquery.propertyGraphs.create</code></li>
<li><code>bigquery.propertyGraphs.delete</code></li>
<li><code>bigquery.propertyGraphs.get</code></li>
<li><code>bigquery.propertyGraphs.list</code></li>
<li><code>bigquery.propertyGraphs.update</code></li>
</ul>
<p><code>bigquery.readsessions.*</code></p>
<ul>
<li><code>bigquery.readsessions.create</code></li>
<li><code>bigquery.readsessions.getData</code></li>
<li><code>bigquery.readsessions.update</code></li>
</ul>
<p><code>bigquery. reservationAssignments.*</code></p>
<ul>
<li><code>bigquery. reservationAssignments. create</code></li>
<li><code>bigquery. reservationAssignments. delete</code></li>
<li><code>bigquery. reservationAssignments. list</code></li>
<li><code>bigquery. reservationAssignments. search</code></li>
</ul>
<p><code>bigquery.reservationGroups.*</code></p>
<ul>
<li><code>bigquery. reservationGroups. create</code></li>
<li><code>bigquery. reservationGroups. delete</code></li>
<li><code>bigquery.reservationGroups.get</code></li>
<li><code>bigquery. reservationGroups. list</code></li>
<li><code>bigquery. reservationGroups. update</code></li>
</ul>
<p><code>bigquery.reservations.*</code></p>
<ul>
<li><code>bigquery.reservations.create</code></li>
<li><code>bigquery.reservations.delete</code></li>
<li><code>bigquery.reservations.get</code></li>
<li><code>bigquery. reservations. getIamPolicy</code></li>
<li><code>bigquery.reservations.list</code></li>
<li><code>bigquery. reservations. listFailoverDatasets</code></li>
<li><code>bigquery. reservations. setIamPolicy</code></li>
<li><code>bigquery.reservations.update</code></li>
<li><code>bigquery.reservations.use</code></li>
</ul>
<p><code>bigquery.routines.*</code></p>
<ul>
<li><code>bigquery.routines.create</code></li>
<li><code>bigquery.routines.delete</code></li>
<li><code>bigquery.routines.get</code></li>
<li><code>bigquery.routines.list</code></li>
<li><code>bigquery.routines.update</code></li>
<li><code>bigquery.routines.updateTag</code></li>
</ul>
<p><code>bigquery. rowAccessPolicies. create</code></p>
<p><code>bigquery. rowAccessPolicies. delete</code></p>
<p><code>bigquery.rowAccessPolicies.get</code></p>
<p><code>bigquery. rowAccessPolicies. getIamPolicy</code></p>
<p><code>bigquery. rowAccessPolicies. list</code></p>
<p><code>bigquery. rowAccessPolicies. overrideTimeTravelRestrictions</code></p>
<p><code>bigquery. rowAccessPolicies. setIamPolicy</code></p>
<p><code>bigquery. rowAccessPolicies. update</code></p>
<p><code>bigquery.savedqueries.*</code></p>
<ul>
<li><code>bigquery.savedqueries.create</code></li>
<li><code>bigquery.savedqueries.delete</code></li>
<li><code>bigquery.savedqueries.get</code></li>
<li><code>bigquery.savedqueries.list</code></li>
<li><code>bigquery.savedqueries.update</code></li>
</ul>
<p><code>bigquery.tables.*</code></p>
<ul>
<li><code>bigquery.tables.create</code></li>
<li><code>bigquery.tables.createIndex</code></li>
<li><code>bigquery.tables.createSnapshot</code></li>
<li><code>bigquery. tables. createTagBinding</code></li>
<li><code>bigquery.tables.delete</code></li>
<li><code>bigquery.tables.deleteIndex</code></li>
<li><code>bigquery.tables.deleteSnapshot</code></li>
<li><code>bigquery. tables. deleteTagBinding</code></li>
<li><code>bigquery.tables.export</code></li>
<li><code>bigquery.tables.get</code></li>
<li><code>bigquery.tables.getData</code></li>
<li><code>bigquery.tables.getIamPolicy</code></li>
<li><code>bigquery.tables.list</code></li>
<li><code>bigquery. tables. listEffectiveTags</code></li>
<li><code>bigquery. tables. listTagBindings</code></li>
<li><code>bigquery.tables.replicateData</code></li>
<li><code>bigquery. tables. restoreSnapshot</code></li>
<li><code>bigquery.tables.setCategory</code></li>
<li><code>bigquery. tables. setColumnDataPolicy</code></li>
<li><code>bigquery.tables.setIamPolicy</code></li>
<li><code>bigquery.tables.update</code></li>
<li><code>bigquery.tables.updateData</code></li>
<li><code>bigquery.tables.updateIndex</code></li>
<li><code>bigquery.tables.updateTag</code></li>
</ul>
<p><code>bigquery.transfers.*</code></p>
<ul>
<li><code>bigquery.transfers.get</code></li>
<li><code>bigquery.transfers.update</code></li>
</ul>
<p><code>bigquerymigration. translation. translate</code></p>
<p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>datacatalog.catalogs.searchAll</code></p>
<p><code>datacatalog. categories. getIamPolicy</code></p>
<p><code>datacatalog. categories. setIamPolicy</code></p>
<p><code>datacatalog.entries.get</code></p>
<p><code>datacatalog.taxonomies.create</code></p>
<p><code>datacatalog.taxonomies.delete</code></p>
<p><code>datacatalog.taxonomies.get</code></p>
<p><code>datacatalog.taxonomies.list</code></p>
<p><code>datacatalog.taxonomies.update</code></p>
<p><code>dataform.*</code></p>
<ul>
<li><code>dataform.commentThreads.create</code></li>
<li><code>dataform.commentThreads.delete</code></li>
<li><code>dataform.commentThreads.get</code></li>
<li><code>dataform.commentThreads.list</code></li>
<li><code>dataform.commentThreads.update</code></li>
<li><code>dataform.comments.create</code></li>
<li><code>dataform.comments.delete</code></li>
<li><code>dataform.comments.get</code></li>
<li><code>dataform.comments.list</code></li>
<li><code>dataform.comments.update</code></li>
<li><code>dataform. compilationResults. create</code></li>
<li><code>dataform. compilationResults. get</code></li>
<li><code>dataform. compilationResults. list</code></li>
<li><code>dataform. compilationResults. query</code></li>
<li><code>dataform.config.get</code></li>
<li><code>dataform.config.update</code></li>
<li><code>dataform.folders.addContents</code></li>
<li><code>dataform.folders.create</code></li>
<li><code>dataform.folders.delete</code></li>
<li><code>dataform.folders.deleteTree</code></li>
<li><code>dataform.folders.get</code></li>
<li><code>dataform.folders.getIamPolicy</code></li>
<li><code>dataform.folders.move</code></li>
<li><code>dataform.folders.queryContents</code></li>
<li><code>dataform.folders.setIamPolicy</code></li>
<li><code>dataform.folders.update</code></li>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
<li><code>dataform.operations.cancel</code></li>
<li><code>dataform.operations.delete</code></li>
<li><code>dataform.operations.get</code></li>
<li><code>dataform.operations.list</code></li>
<li><code>dataform.releaseConfigs.create</code></li>
<li><code>dataform.releaseConfigs.delete</code></li>
<li><code>dataform.releaseConfigs.get</code></li>
<li><code>dataform.releaseConfigs.list</code></li>
<li><code>dataform.releaseConfigs.update</code></li>
<li><code>dataform.repositories.commit</code></li>
<li><code>dataform. repositories. computeAccessTokenStatus</code></li>
<li><code>dataform.repositories.create</code></li>
<li><code>dataform. repositories. createTagBinding</code></li>
<li><code>dataform.repositories.delete</code></li>
<li><code>dataform. repositories. deleteTagBinding</code></li>
<li><code>dataform. repositories. fetchHistory</code></li>
<li><code>dataform. repositories. fetchRemoteBranches</code></li>
<li><code>dataform.repositories.get</code></li>
<li><code>dataform. repositories. getIamPolicy</code></li>
<li><code>dataform.repositories.list</code></li>
<li><code>dataform. repositories. listEffectiveTags</code></li>
<li><code>dataform. repositories. listTagBindings</code></li>
<li><code>dataform.repositories.move</code></li>
<li><code>dataform. repositories. queryDirectoryContents</code></li>
<li><code>dataform.repositories.readFile</code></li>
<li><code>dataform. repositories. scheduleRelease</code></li>
<li><code>dataform. repositories. scheduleWorkflow</code></li>
<li><code>dataform. repositories. setIamPolicy</code></li>
<li><code>dataform.repositories.update</code></li>
<li><code>dataform.teamFolders.create</code></li>
<li><code>dataform.teamFolders.delete</code></li>
<li><code>dataform. teamFolders. deleteTree</code></li>
<li><code>dataform.teamFolders.get</code></li>
<li><code>dataform. teamFolders. getIamPolicy</code></li>
<li><code>dataform. teamFolders. setIamPolicy</code></li>
<li><code>dataform.teamFolders.update</code></li>
<li><code>dataform. workflowConfigs. create</code></li>
<li><code>dataform. workflowConfigs. delete</code></li>
<li><code>dataform.workflowConfigs.get</code></li>
<li><code>dataform.workflowConfigs.list</code></li>
<li><code>dataform. workflowConfigs. update</code></li>
<li><code>dataform. workflowInvocations. cancel</code></li>
<li><code>dataform. workflowInvocations. create</code></li>
<li><code>dataform. workflowInvocations. delete</code></li>
<li><code>dataform. workflowInvocations. get</code></li>
<li><code>dataform. workflowInvocations. list</code></li>
<li><code>dataform. workflowInvocations. query</code></li>
<li><code>dataform.workspaces.commit</code></li>
<li><code>dataform.workspaces.create</code></li>
<li><code>dataform.workspaces.delete</code></li>
<li><code>dataform. workspaces. fetchFileDiff</code></li>
<li><code>dataform. workspaces. fetchFileGitStatuses</code></li>
<li><code>dataform. workspaces. fetchGitAheadBehind</code></li>
<li><code>dataform.workspaces.get</code></li>
<li><code>dataform. workspaces. getIamPolicy</code></li>
<li><code>dataform. workspaces. installNpmPackages</code></li>
<li><code>dataform.workspaces.list</code></li>
<li><code>dataform. workspaces. makeDirectory</code></li>
<li><code>dataform. workspaces. moveDirectory</code></li>
<li><code>dataform.workspaces.moveFile</code></li>
<li><code>dataform.workspaces.pull</code></li>
<li><code>dataform.workspaces.push</code></li>
<li><code>dataform. workspaces. queryDirectoryContents</code></li>
<li><code>dataform.workspaces.readFile</code></li>
<li><code>dataform. workspaces. removeDirectory</code></li>
<li><code>dataform.workspaces.removeFile</code></li>
<li><code>dataform.workspaces.reset</code></li>
<li><code>dataform. workspaces. searchFiles</code></li>
<li><code>dataform. workspaces. setIamPolicy</code></li>
<li><code>dataform.workspaces.writeFile</code></li>
</ul>
<p><code>dataplex.assets.getIamPolicy</code></p>
<p><code>dataplex.datascans.*</code></p>
<ul>
<li><code>dataplex.datascans.cancel</code></li>
<li><code>dataplex.datascans.create</code></li>
<li><code>dataplex.datascans.delete</code></li>
<li><code>dataplex.datascans.get</code></li>
<li><code>dataplex.datascans.getData</code></li>
<li><code>dataplex. datascans. getIamPolicy</code></li>
<li><code>dataplex.datascans.list</code></li>
<li><code>dataplex.datascans.run</code></li>
<li><code>dataplex. datascans. setIamPolicy</code></li>
<li><code>dataplex.datascans.update</code></li>
</ul>
<p><code>dataplex.environments.execute</code></p>
<p><code>dataplex.environments.get</code></p>
<p><code>dataplex.environments.list</code></p>
<p><code>dataplex.lakes.get</code></p>
<p><code>dataplex.lakes.getIamPolicy</code></p>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.operations.list</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>dataplex.zones.getIamPolicy</code></p>
<p><code>dataproc.agents.*</code></p>
<ul>
<li><code>dataproc.agents.create</code></li>
<li><code>dataproc.agents.delete</code></li>
<li><code>dataproc.agents.get</code></li>
<li><code>dataproc.agents.list</code></li>
<li><code>dataproc.agents.update</code></li>
</ul>
<p><code>dataproc.batches.cancel</code></p>
<p><code>dataproc.batches.create</code></p>
<p><code>dataproc.batches.get</code></p>
<p><code>dataproc.operations.cancel</code></p>
<p><code>dataproc.operations.get</code></p>
<p><code>dataproc.operations.list</code></p>
<p><code>dataproc.tasks.*</code></p>
<ul>
<li><code>dataproc.tasks.lease</code></li>
<li><code>dataproc. tasks. listInvalidatedLeases</code></li>
<li><code>dataproc.tasks.reportStatus</code></li>
</ul>
<p><code>firebase.projects.get</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>metastore.services.get</code></p>
<p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring.groups.get</code></p>
<p><code>monitoring.groups.list</code></p>
<p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.*</code></p>
<ul>
<li><code>monitoring.timeSeries.create</code></li>
<li><code>monitoring.timeSeries.list</code></li>
</ul>
<p><code>orgpolicy.policy.get</code></p>
<p><code>recommender. iamPolicyInsights.*</code></p>
<ul>
<li><code>recommender. iamPolicyInsights. get</code></li>
<li><code>recommender. iamPolicyInsights. list</code></li>
<li><code>recommender. iamPolicyInsights. update</code></li>
</ul>
<p><code>recommender. iamPolicyRecommendations.*</code></p>
<ul>
<li><code>recommender. iamPolicyRecommendations. get</code></li>
<li><code>recommender. iamPolicyRecommendations. list</code></li>
<li><code>recommender. iamPolicyRecommendations. update</code></li>
</ul>
<p><code>recommender. storageBucketSoftDeleteInsights.*</code></p>
<ul>
<li><code>recommender. storageBucketSoftDeleteInsights. get</code></li>
<li><code>recommender. storageBucketSoftDeleteInsights. list</code></li>
<li><code>recommender. storageBucketSoftDeleteInsights. update</code></li>
</ul>
<p><code>recommender. storageBucketSoftDeleteRecommendations.*</code></p>
<ul>
<li><code>recommender. storageBucketSoftDeleteRecommendations. get</code></li>
<li><code>recommender. storageBucketSoftDeleteRecommendations. list</code></li>
<li><code>recommender. storageBucketSoftDeleteRecommendations. update</code></li>
</ul>
<p><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>servicemanagement. services. report</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>stackdriver.projects.get</code></p>
<p><code>stackdriver. resourceMetadata. list</code></p>
<p><code>storage.anywhereCaches.*</code></p>
<ul>
<li><code>storage.anywhereCaches.create</code></li>
<li><code>storage.anywhereCaches.disable</code></li>
<li><code>storage.anywhereCaches.get</code></li>
<li><code>storage.anywhereCaches.list</code></li>
<li><code>storage.anywhereCaches.pause</code></li>
<li><code>storage.anywhereCaches.resume</code></li>
<li><code>storage.anywhereCaches.update</code></li>
</ul>
<p><code>storage.bucketOperations.*</code></p>
<ul>
<li><code>storage. bucketOperations. cancel</code></li>
<li><code>storage.bucketOperations.get</code></li>
<li><code>storage.bucketOperations.list</code></li>
</ul>
<p><code>storage.buckets.*</code></p>
<ul>
<li><code>storage.buckets.create</code></li>
<li><code>storage. buckets. createTagBinding</code></li>
<li><code>storage.buckets.delete</code></li>
<li><code>storage. buckets. deleteTagBinding</code></li>
<li><code>storage. buckets. enableObjectRetention</code></li>
<li><code>storage.buckets.get</code></li>
<li><code>storage.buckets.getIamPolicy</code></li>
<li><code>storage.buckets.getIpFilter</code></li>
<li><code>storage. buckets. getObjectInsights</code></li>
<li><code>storage.buckets.list</code></li>
<li><code>storage. buckets. listEffectiveTags</code></li>
<li><code>storage. buckets. listTagBindings</code></li>
<li><code>storage.buckets.relocate</code></li>
<li><code>storage.buckets.restore</code></li>
<li><code>storage.buckets.setIamPolicy</code></li>
<li><code>storage.buckets.setIpFilter</code></li>
<li><code>storage.buckets.update</code></li>
<li><code>storage. buckets. viewIntelligenceDetails</code></li>
<li><code>storage. buckets. viewSecurityIntelligenceDetails</code></li>
</ul>
<p><code>storage.featureConfigs.*</code></p>
<ul>
<li><code>storage.featureConfigs.create</code></li>
<li><code>storage.featureConfigs.delete</code></li>
<li><code>storage.featureConfigs.get</code></li>
<li><code>storage.featureConfigs.list</code></li>
<li><code>storage.featureConfigs.update</code></li>
</ul>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
</ul>
<p><code>storage.intelligenceConfigs.*</code></p>
<ul>
<li><code>storage. intelligenceConfigs. get</code></li>
<li><code>storage. intelligenceConfigs. update</code></li>
</ul>
<p><code>storage.managedFolders.*</code></p>
<ul>
<li><code>storage.managedFolders.create</code></li>
<li><code>storage.managedFolders.delete</code></li>
<li><code>storage.managedFolders.get</code></li>
<li><code>storage. managedFolders. getIamPolicy</code></li>
<li><code>storage.managedFolders.list</code></li>
<li><code>storage. managedFolders. setIamPolicy</code></li>
<li><code>storage.managedFolders.update</code></li>
</ul>
<p><code>storage.multipartUploads.*</code></p>
<ul>
<li><code>storage.multipartUploads.abort</code></li>
<li><code>storage. multipartUploads. create</code></li>
<li><code>storage.multipartUploads.list</code></li>
<li><code>storage. multipartUploads. listParts</code></li>
</ul>
<p><code>storage.objects.*</code></p>
<ul>
<li><code>storage.objects.create</code></li>
<li><code>storage.objects.createContext</code></li>
<li><code>storage.objects.delete</code></li>
<li><code>storage.objects.deleteContext</code></li>
<li><code>storage.objects.get</code></li>
<li><code>storage.objects.getIamPolicy</code></li>
<li><code>storage.objects.list</code></li>
<li><code>storage.objects.move</code></li>
<li><code>storage. objects. overrideUnlockedRetention</code></li>
<li><code>storage.objects.restore</code></li>
<li><code>storage.objects.setIamPolicy</code></li>
<li><code>storage.objects.setRetention</code></li>
<li><code>storage.objects.update</code></li>
<li><code>storage.objects.updateContext</code></li>
</ul>
<p><code>storagebatchoperations.*</code></p>
<ul>
<li><code>storagebatchoperations. bucketOperations. get</code></li>
<li><code>storagebatchoperations. bucketOperations. list</code></li>
<li><code>storagebatchoperations. jobs. cancel</code></li>
<li><code>storagebatchoperations. jobs. create</code></li>
<li><code>storagebatchoperations. jobs. delete</code></li>
<li><code>storagebatchoperations. jobs. get</code></li>
<li><code>storagebatchoperations. jobs. list</code></li>
<li><code>storagebatchoperations. locations. get</code></li>
<li><code>storagebatchoperations. locations. list</code></li>
<li><code>storagebatchoperations. operations. cancel</code></li>
<li><code>storagebatchoperations. operations. delete</code></li>
<li><code>storagebatchoperations. operations. get</code></li>
<li><code>storagebatchoperations. operations. list</code></li>
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
<td><code>dataplex.aspectTypes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateCreator">Data Catalog TagTemplate Creator</a> ( <code>roles/ datacatalog.tagTemplateCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
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
<td><code>dataplex.aspectTypes.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
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
<td><code>dataplex.aspectTypes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateCreator">Data Catalog TagTemplate Creator</a> ( <code>roles/ datacatalog.tagTemplateCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code>roles/ datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code>roles/ datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code>roles/ dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
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
<tr class="even">
<td><code>dataplex. aspectTypes. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
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
<tr class="odd">
<td><code>dataplex.aspectTypes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code>roles/ datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code>roles/ datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code>roles/ dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
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
<td><code>dataplex. aspectTypes. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex.aspectTypes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
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
<td><code>dataplex.aspectTypes.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code>roles/ datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code>roles/ dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
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
<td><code>dataplex.assetActions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.assets.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.assets.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.assets.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code>roles/ dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.assets.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex.assets.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code>roles/ dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.assets.ownData</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataOwner">Dataplex Data Owner</a> ( <code>roles/ dataplex.dataOwner</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.assets.readData</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataOwner">Dataplex Data Owner</a> ( <code>roles/ dataplex.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataReader">Dataplex Data Reader</a> ( <code>roles/ dataplex.dataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.assets.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.assets.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.assets.writeData</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataOwner">Dataplex Data Owner</a> ( <code>roles/ dataplex.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataWriter">Dataplex Data Writer</a> ( <code>roles/ dataplex.dataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. changeRequests. adminDelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.workflowAdmin">Dataplex Workflow Admin</a> ( <code>roles/ dataplex.workflowAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.changeRequests.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.changeRequestOwner">Dataplex Change Request Owner</a> ( <code>roles/ dataplex.changeRequestOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.workflowAdmin">Dataplex Workflow Admin</a> ( <code>roles/ dataplex.workflowAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.changeRequests.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.changeRequestOwner">Dataplex Change Request Owner</a> ( <code>roles/ dataplex.changeRequestOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.workflowAdmin">Dataplex Workflow Admin</a> ( <code>roles/ dataplex.workflowAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.workflowApprover">Dataplex Workflow Approver</a> ( <code>roles/ dataplex.workflowApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. changeRequests. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.changeRequests.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.workflowAdmin">Dataplex Workflow Admin</a> ( <code>roles/ dataplex.workflowAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.workflowApprover">Dataplex Workflow Approver</a> ( <code>roles/ dataplex.workflowApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. changeRequests. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.changeRequests.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.changeRequestOwner">Dataplex Change Request Owner</a> ( <code>roles/ dataplex.changeRequestOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.changeRequests.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.workflowAdmin">Dataplex Workflow Admin</a> ( <code>roles/ dataplex.workflowAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.workflowApprover">Dataplex Workflow Approver</a> ( <code>roles/ dataplex.workflowApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.content.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.content.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.content.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.content.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.content.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.content.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.content.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataAssets.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataAssets.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataAssets.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsConsumer">Dataplex Data Products Consumer</a> ( <code>roles/ dataplex.dataProductsConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code>roles/ dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataAssets.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsConsumer">Dataplex Data Products Consumer</a> ( <code>roles/ dataplex.dataProductsConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code>roles/ dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataAssets.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. dataAttributeBindings. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code>roles/ dataplex.bindingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataAttributeBindings. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code>roles/ dataplex.bindingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. dataAttributeBindings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code>roles/ dataplex.bindingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataAttributeBindings. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code>roles/ dataplex.bindingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. dataAttributeBindings. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code>roles/ dataplex.bindingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataAttributeBindings. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code>roles/ dataplex.bindingAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. dataAttributeBindings. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.bindingAdmin">Dataplex Binding Administrator</a> ( <code>roles/ dataplex.bindingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataAttributes.bind</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataAttributes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataAttributes.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataAttributes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyViewer">Dataplex Taxonomy Viewer</a> ( <code>roles/ dataplex.taxonomyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataAttributes. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyViewer">Dataplex Taxonomy Viewer</a> ( <code>roles/ dataplex.taxonomyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataAttributes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyViewer">Dataplex Taxonomy Viewer</a> ( <code>roles/ dataplex.taxonomyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataAttributes. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataAttributes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataDomainBindings. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. dataDomainBindings. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataDomainBindings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainViewer">Dataplex Data Domain Configuration Viewer</a> ( <code>roles/ dataplex.dataDomainViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. dataDomainBindings. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainViewer">Dataplex Data Domain Configuration Viewer</a> ( <code>roles/ dataplex.dataDomainViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataDomains.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataDomains.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataDomains.discover</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code>roles/ datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code>roles/ dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEntryReader">Dataplex Data Domain Entry Reader</a> ( <code>roles/ dataplex.dataDomainEntryReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainViewer">Dataplex Data Domain Configuration Viewer</a> ( <code>roles/ dataplex.dataDomainViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeUser">Dataplex Entry Link Type User</a> ( <code>roles/ dataplex.entryLinkTypeUser</code> )</p>
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
<tr class="even">
<td><code>dataplex.dataDomains.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEntryReader">Dataplex Data Domain Entry Reader</a> ( <code>roles/ dataplex.dataDomainEntryReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainViewer">Dataplex Data Domain Configuration Viewer</a> ( <code>roles/ dataplex.dataDomainViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataDomains. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainViewer">Dataplex Data Domain Configuration Viewer</a> ( <code>roles/ dataplex.dataDomainViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataDomains.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEntryReader">Dataplex Data Domain Entry Reader</a> ( <code>roles/ dataplex.dataDomainEntryReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainViewer">Dataplex Data Domain Configuration Viewer</a> ( <code>roles/ dataplex.dataDomainViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataDomains. lookupEntry</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEntryReader">Dataplex Data Domain Entry Reader</a> ( <code>roles/ dataplex.dataDomainEntryReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainViewer">Dataplex Data Domain Configuration Viewer</a> ( <code>roles/ dataplex.dataDomainViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. dataDomains. modifyEntry</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataDomains. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataDomains.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataProducts.approve</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataProducts.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataProducts.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataProducts.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsConsumer">Dataplex Data Products Consumer</a> ( <code>roles/ dataplex.dataProductsConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code>roles/ dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataProducts. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code>roles/ dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataProducts.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code>roles/ dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataProducts. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataProducts.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. dataTaxonomies. configureDataAccess</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.securityAdmin">Dataplex Security Administrator</a> ( <code>roles/ dataplex.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. dataTaxonomies. configureResourceAccess</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.securityAdmin">Dataplex Security Administrator</a> ( <code>roles/ dataplex.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataTaxonomies.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.dataTaxonomies.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataTaxonomies.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyViewer">Dataplex Taxonomy Viewer</a> ( <code>roles/ dataplex.taxonomyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. dataTaxonomies. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyViewer">Dataplex Taxonomy Viewer</a> ( <code>roles/ dataplex.taxonomyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataTaxonomies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyViewer">Dataplex Taxonomy Viewer</a> ( <code>roles/ dataplex.taxonomyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. dataTaxonomies. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.dataTaxonomies.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.taxonomyAdmin">Dataplex Taxonomy Administrator</a> ( <code>roles/ dataplex.taxonomyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.datascans.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code>roles/ dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex.datascans.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanCreator">Dataplex DataScan Creator</a> ( <code>roles/ dataplex.dataScanCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code>roles/ dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex.datascans.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code>roles/ dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex.datascans.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataViewer">BigQuery Data Viewer</a> ( <code>roles/ bigquery.dataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanCreator">Dataplex DataScan Creator</a> ( <code>roles/ dataplex.dataScanCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanDataViewer">Dataplex DataScan DataViewer</a> ( <code>roles/ dataplex.dataScanDataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code>roles/ dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanViewer">Dataplex DataScan Viewer</a> ( <code>roles/ dataplex.dataScanViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex.datascans.getData</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataViewer">BigQuery Data Viewer</a> ( <code>roles/ bigquery.dataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanDataViewer">Dataplex DataScan DataViewer</a> ( <code>roles/ dataplex.dataScanDataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code>roles/ dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex. datascans. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataViewer">BigQuery Data Viewer</a> ( <code>roles/ bigquery.dataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanDataViewer">Dataplex DataScan DataViewer</a> ( <code>roles/ dataplex.dataScanDataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code>roles/ dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanViewer">Dataplex DataScan Viewer</a> ( <code>roles/ dataplex.dataScanViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex.datascans.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataViewer">BigQuery Data Viewer</a> ( <code>roles/ bigquery.dataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanCreator">Dataplex DataScan Creator</a> ( <code>roles/ dataplex.dataScanCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanDataViewer">Dataplex DataScan DataViewer</a> ( <code>roles/ dataplex.dataScanDataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code>roles/ dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanViewer">Dataplex DataScan Viewer</a> ( <code>roles/ dataplex.dataScanViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex.datascans.run</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code>roles/ dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex. datascans. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex.datascans.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code>roles/ dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex. encryptionConfig. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code>roles/ dataplex.encryptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. encryptionConfig. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code>roles/ dataplex.encryptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.encryptionConfig.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code>roles/ dataplex.encryptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.encryptionConfig.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code>roles/ dataplex.encryptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. encryptionConfig. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code>roles/ dataplex.encryptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entities.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entities.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entities.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code>roles/ dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entities.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code>roles/ dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entities.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entries.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entries.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entries.get</code></td>
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
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
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
<td><code>dataplex.entries.getData</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entries.link</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entries.list</code></td>
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
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entries.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagEditor">Data Catalog Tag Editor</a> ( <code>roles/ datacatalog.tagEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entryGroups.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code>roles/ datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entryGroups.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entryGroups.export</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupExporter">Dataplex Entry Group Exporter</a> ( <code>roles/ dataplex.entryGroupExporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entryGroups.get</code></td>
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
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupExporter">Dataplex Entry Group Exporter</a> ( <code>roles/ dataplex.entryGroupExporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupImporter">Dataplex Entry Group Importer</a> ( <code>roles/ dataplex.entryGroupImporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entryGroups.import</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupImporter">Dataplex Entry Group Importer</a> ( <code>roles/ dataplex.entryGroupImporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entryGroups.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. requestChanges</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entryGroups.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useContactsAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code>roles/ datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useContextAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useContextEntry</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useContextEntryLink</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useDataProfileAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useDataQualityRuleTemplateAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useDataQualityRuleTemplateEntry</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useDataQualityScorecardAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useDataRulesAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useDatabaseDataPolicyAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useDefinitionEntryLink</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useDescriptionsAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useGenericAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useGenericEntry</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useGraphProfileAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useManagedConnectorTypes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useMySQLConnectorTypes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useOracleConnectorTypes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useOverviewAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code>roles/ datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. usePostgreSQLConnectorTypes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useQueriesAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useRefreshCadenceAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useRelatedEntryLink</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useSQLAccessAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useSQLServerConnectorTypes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useSQLTriggersAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useSchemaAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useSchemaJoinAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useSchemaJoinEntryLink</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useSecondaryIndexesAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryGroups. useStorageAspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex. entryGroups. useSynonymEntryLink</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entryLinkTypes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entryLinkTypes.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entryLinkTypes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeUser">Dataplex Entry Link Type User</a> ( <code>roles/ dataplex.entryLinkTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryLinkTypes. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entryLinkTypes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeUser">Dataplex Entry Link Type User</a> ( <code>roles/ dataplex.entryLinkTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryLinkTypes. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entryLinkTypes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entryLinkTypes.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeUser">Dataplex Entry Link Type User</a> ( <code>roles/ dataplex.entryLinkTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entryLinks.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entryLinks.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entryLinks.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entryLinks.reference</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entryLinks.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entryTypes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryTypes. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entryTypes.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryTypes. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entryTypes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code>roles/ dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryTypes. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entryTypes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code>roles/ dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryTypes. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code>roles/ dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. entryTypes. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code>roles/ dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. entryTypes. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.entryTypes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.entryTypes.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code>roles/ dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.environments.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.environments.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.environments.execute</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
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
<td><code>dataplex.environments.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
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
<td><code>dataplex. environments. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.environments.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
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
<td><code>dataplex. environments. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.environments.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.glossaries.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.glossaries.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.glossaries.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. glossaries. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.glossaries.import</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.glossaries.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. glossaries. requestChanges</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. glossaries. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.glossaries.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. glossaryCategories. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. glossaryCategories. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. glossaryCategories. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. glossaryCategories. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. glossaryCategories. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.glossaryTerms.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.glossaryTerms.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.glossaryTerms.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.glossaryTerms.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.glossaryTerms.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.glossaryTerms.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. governanceRules. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. governanceRules. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex. governanceRules. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex. governanceRules. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.lakeActions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.lakes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.lakes.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.lakes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
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
<td><code>dataplex.lakes.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex.lakes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.lakes.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.lakes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.metadataFeeds.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code>roles/ dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.metadataFeeds.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code>roles/ dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.metadataFeeds.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code>roles/ dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedViewer">Dataplex Metadata Feed Viewer</a> ( <code>roles/ dataplex.metadataFeedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.metadataFeeds.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code>roles/ dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedViewer">Dataplex Metadata Feed Viewer</a> ( <code>roles/ dataplex.metadataFeedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.metadataFeeds.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code>roles/ dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.metadataJobs.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code>roles/ dataplex.metadataJobOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.metadataJobs.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code>roles/ dataplex.metadataJobOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex.metadataJobs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code>roles/ dataplex.metadataJobOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobViewer">Dataplex Metadata Job Viewer</a> ( <code>roles/ dataplex.metadataJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex.metadataJobs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code>roles/ dataplex.metadataJobOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobViewer">Dataplex Metadata Job Viewer</a> ( <code>roles/ dataplex.metadataJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanCreator">Dataplex DataScan Creator</a> ( <code>roles/ dataplex.dataScanCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code>roles/ dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code>roles/ dataplex.encryptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code>roles/ dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedViewer">Dataplex Metadata Feed Viewer</a> ( <code>roles/ dataplex.metadataFeedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code>roles/ dataplex.metadataJobOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobViewer">Dataplex Metadata Job Viewer</a> ( <code>roles/ dataplex.metadataJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataplex.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanAdmin">Dataplex DataScan Administrator</a> ( <code>roles/ dataplex.dataScanAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataScanEditor">Dataplex DataScan Editor</a> ( <code>roles/ dataplex.dataScanEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.encryptionAdmin">Dataplex Encryption Admin</a> ( <code>roles/ dataplex.encryptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex.partitions.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.partitions.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.partitions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code>roles/ dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.partitions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code>roles/ dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.partitions.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.projects.search</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.metadataViewer">BigQuery Metadata Viewer</a> ( <code>roles/ bigquery.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.securityAdmin">BigQuery Security Admin</a> ( <code>roles/ bigquery.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code>roles/ datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code>roles/ datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code>roles/ datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryOwner">DataCatalog Glossary Owner</a> ( <code>roles/ datacatalog.glossaryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.glossaryUser">DataCatalog Glossary User</a> ( <code>roles/ datacatalog.glossaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.searchAdmin">DataCatalog Search Admin</a> ( <code>roles/ datacatalog.searchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateCreator">Data Catalog TagTemplate Creator</a> ( <code>roles/ datacatalog.tagTemplateCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code>roles/ datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code>roles/ datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code>roles/ dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeUser">Dataplex Entry Link Type User</a> ( <code>roles/ dataplex.entryLinkTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code>roles/ dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex.tasks.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.tasks.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.tasks.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.tasks.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.tasks.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.tasks.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.tasks.run</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.tasks.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.tasks.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.developer">Dataplex Developer</a> ( <code>roles/ dataplex.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.zoneActions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.zones.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.zones.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.zones.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code>roles/ dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.zones.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataplex.zones.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.viewer">Dataplex Viewer</a> ( <code>roles/ dataplex.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code>roles/ dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataplex.zones.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataplex.zones.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.editor">Dataplex Editor</a> ( <code>roles/ dataplex.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
