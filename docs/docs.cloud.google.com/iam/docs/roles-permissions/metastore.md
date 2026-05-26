---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/metastore
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/metastore
title: Dataproc Metastore roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Dataproc Metastore. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Dataproc Metastore roles

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
<td><h4 id="metastore.admin" class="role-title add-link" data-text="Dataproc Metastore Admin" tabindex="-1">Dataproc Metastore Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p>Full access to all Dataproc Metastore resources.</p></td>
<td><p><code dir="ltr" translate="no">metastore.backups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.backups.create</code></li>
<li><code dir="ltr" translate="no">metastore.backups.delete</code></li>
<li><code dir="ltr" translate="no">metastore.backups.get</code></li>
<li><code dir="ltr" translate="no">metastore.backups.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">metastore.backups.list</code></li>
<li><code dir="ltr" translate="no">metastore.backups.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">metastore.backups.use</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.federations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.federations.create</code></li>
<li><code dir="ltr" translate="no">metastore.  federations.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">metastore.federations.delete</code></li>
<li><code dir="ltr" translate="no">metastore.  federations.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">metastore.federations.get</code></li>
<li><code dir="ltr" translate="no">metastore.  federations.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">metastore.federations.list</code></li>
<li><code dir="ltr" translate="no">metastore.  federations.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">metastore.  federations.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">metastore.  federations.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">metastore.federations.update</code></li>
<li><code dir="ltr" translate="no">metastore.federations.use</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.imports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.imports.create</code></li>
<li><code dir="ltr" translate="no">metastore.imports.get</code></li>
<li><code dir="ltr" translate="no">metastore.imports.list</code></li>
<li><code dir="ltr" translate="no">metastore.imports.update</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.locations.get</code></li>
<li><code dir="ltr" translate="no">metastore.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.migrations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.migrations.cancel</code></li>
<li><code dir="ltr" translate="no">metastore.migrations.complete</code></li>
<li><code dir="ltr" translate="no">metastore.migrations.delete</code></li>
<li><code dir="ltr" translate="no">metastore.migrations.get</code></li>
<li><code dir="ltr" translate="no">metastore.migrations.list</code></li>
<li><code dir="ltr" translate="no">metastore.migrations.start</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.operations.cancel</code></li>
<li><code dir="ltr" translate="no">metastore.operations.delete</code></li>
<li><code dir="ltr" translate="no">metastore.operations.get</code></li>
<li><code dir="ltr" translate="no">metastore.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.services.create</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.services.delete</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.services.export</code></p>
<p><code dir="ltr" translate="no">metastore.services.get</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.services.list</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.services.restore</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.services.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.editor" class="role-title add-link" data-text="Dataproc Metastore Editor" tabindex="-1">Dataproc Metastore Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p>Read and write access to all Dataproc Metastore resources.</p></td>
<td><p><code dir="ltr" translate="no">metastore.backups.create</code></p>
<p><code dir="ltr" translate="no">metastore.backups.delete</code></p>
<p><code dir="ltr" translate="no">metastore.backups.get</code></p>
<p><code dir="ltr" translate="no">metastore.backups.list</code></p>
<p><code dir="ltr" translate="no">metastore.backups.use</code></p>
<p><code dir="ltr" translate="no">metastore.federations.create</code></p>
<p><code dir="ltr" translate="no">metastore.federations.delete</code></p>
<p><code dir="ltr" translate="no">metastore.federations.get</code></p>
<p><code dir="ltr" translate="no">metastore.federations.list</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.federations.update</code></p>
<p><code dir="ltr" translate="no">metastore.imports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.imports.create</code></li>
<li><code dir="ltr" translate="no">metastore.imports.get</code></li>
<li><code dir="ltr" translate="no">metastore.imports.list</code></li>
<li><code dir="ltr" translate="no">metastore.imports.update</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.locations.get</code></li>
<li><code dir="ltr" translate="no">metastore.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.migrations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.migrations.cancel</code></li>
<li><code dir="ltr" translate="no">metastore.migrations.complete</code></li>
<li><code dir="ltr" translate="no">metastore.migrations.delete</code></li>
<li><code dir="ltr" translate="no">metastore.migrations.get</code></li>
<li><code dir="ltr" translate="no">metastore.migrations.list</code></li>
<li><code dir="ltr" translate="no">metastore.migrations.start</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.operations.cancel</code></li>
<li><code dir="ltr" translate="no">metastore.operations.delete</code></li>
<li><code dir="ltr" translate="no">metastore.operations.get</code></li>
<li><code dir="ltr" translate="no">metastore.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.services.create</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.services.delete</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.services.export</code></p>
<p><code dir="ltr" translate="no">metastore.services.get</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.services.list</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.services.restore</code></p>
<p><code dir="ltr" translate="no">metastore.services.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.viewer" class="role-title add-link" data-text="Dataproc Metastore Viewer" tabindex="-1">Dataproc Metastore Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p>Viewer role for Dataproc Metastore</p></td>
<td><p><code dir="ltr" translate="no">metastore.backups.get</code></p>
<p><code dir="ltr" translate="no">metastore.backups.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.backups.list</code></p>
<p><code dir="ltr" translate="no">metastore.backups.use</code></p>
<p><code dir="ltr" translate="no">metastore.databases.get</code></p>
<p><code dir="ltr" translate="no">metastore.  databases.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.databases.list</code></p>
<p><code dir="ltr" translate="no">metastore.federations.get</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.federations.list</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.imports.get</code></p>
<p><code dir="ltr" translate="no">metastore.imports.list</code></p>
<p><code dir="ltr" translate="no">metastore.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.locations.get</code></li>
<li><code dir="ltr" translate="no">metastore.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.migrations.get</code></p>
<p><code dir="ltr" translate="no">metastore.migrations.list</code></p>
<p><code dir="ltr" translate="no">metastore.operations.get</code></p>
<p><code dir="ltr" translate="no">metastore.operations.list</code></p>
<p><code dir="ltr" translate="no">metastore.services.export</code></p>
<p><code dir="ltr" translate="no">metastore.services.get</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.services.list</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.tables.get</code></p>
<p><code dir="ltr" translate="no">metastore.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.tables.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.federationAccessor" class="role-title add-link" data-text="Metastore Federation Accessor" tabindex="-1">Metastore Federation Accessor</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.federationAccessor</code> )</p>
<p>Access to the Metastore Federation resource.</p></td>
<td><p><code dir="ltr" translate="no">metastore.federations.use</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.metadataEditor" class="role-title add-link" data-text="Dataproc Metastore Metadata Editor" tabindex="-1">Dataproc Metastore Metadata Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p>Access to read and modify the metadata of databases and tables under those databases.</p></td>
<td><p><code dir="ltr" translate="no">metastore.databases.create</code></p>
<p><code dir="ltr" translate="no">metastore.databases.delete</code></p>
<p><code dir="ltr" translate="no">metastore.databases.get</code></p>
<p><code dir="ltr" translate="no">metastore.  databases.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.databases.list</code></p>
<p><code dir="ltr" translate="no">metastore.databases.update</code></p>
<p><code dir="ltr" translate="no">metastore.services.get</code></p>
<p><code dir="ltr" translate="no">metastore.services.use</code></p>
<p><code dir="ltr" translate="no">metastore.tables.create</code></p>
<p><code dir="ltr" translate="no">metastore.tables.delete</code></p>
<p><code dir="ltr" translate="no">metastore.tables.get</code></p>
<p><code dir="ltr" translate="no">metastore.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.tables.list</code></p>
<p><code dir="ltr" translate="no">metastore.tables.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.metadataMutateAdmin" class="role-title add-link" data-text="Dataproc Metastore Metadata Mutate Admin" tabindex="-1">Dataproc Metastore Metadata Mutate Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.metadataMutateAdmin</code> )</p>
<p>Access to mutate metadata from a Dataproc Metastore service's underlying metadata store.</p></td>
<td><p><code dir="ltr" translate="no">metastore.  services.  mutateMetadata</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.metadataOperator" class="role-title add-link" data-text="Dataproc Metastore Metadata Operator" tabindex="-1">Dataproc Metastore Metadata Operator</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p>Read-only access to Dataproc Metastore resources with additional metadata operations permission.</p></td>
<td><p><code dir="ltr" translate="no">metastore.backups.create</code></p>
<p><code dir="ltr" translate="no">metastore.backups.delete</code></p>
<p><code dir="ltr" translate="no">metastore.backups.get</code></p>
<p><code dir="ltr" translate="no">metastore.backups.list</code></p>
<p><code dir="ltr" translate="no">metastore.backups.use</code></p>
<p><code dir="ltr" translate="no">metastore.imports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.imports.create</code></li>
<li><code dir="ltr" translate="no">metastore.imports.get</code></li>
<li><code dir="ltr" translate="no">metastore.imports.list</code></li>
<li><code dir="ltr" translate="no">metastore.imports.update</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.locations.get</code></li>
<li><code dir="ltr" translate="no">metastore.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.operations.get</code></p>
<p><code dir="ltr" translate="no">metastore.operations.list</code></p>
<p><code dir="ltr" translate="no">metastore.services.export</code></p>
<p><code dir="ltr" translate="no">metastore.services.get</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.services.list</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.services.restore</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.metadataOwner" class="role-title add-link" data-text="Dataproc Metastore Data Owner" tabindex="-1">Dataproc Metastore Data Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p>Full access to the metadata of databases and tables under those databases.</p></td>
<td><p><code dir="ltr" translate="no">metastore.databases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.databases.create</code></li>
<li><code dir="ltr" translate="no">metastore.databases.delete</code></li>
<li><code dir="ltr" translate="no">metastore.databases.get</code></li>
<li><code dir="ltr" translate="no">metastore.  databases.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">metastore.databases.list</code></li>
<li><code dir="ltr" translate="no">metastore.  databases.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">metastore.databases.update</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.services.get</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.services.list</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.services.use</code></p>
<p><code dir="ltr" translate="no">metastore.tables.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.tables.create</code></li>
<li><code dir="ltr" translate="no">metastore.tables.delete</code></li>
<li><code dir="ltr" translate="no">metastore.tables.get</code></li>
<li><code dir="ltr" translate="no">metastore.tables.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">metastore.tables.list</code></li>
<li><code dir="ltr" translate="no">metastore.tables.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">metastore.tables.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.metadataQueryAdmin" class="role-title add-link" data-text="Dataproc Metastore Metadata Query Admin" tabindex="-1">Dataproc Metastore Metadata Query Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.metadataQueryAdmin</code> )</p>
<p>Access to query metadata from a Dataproc Metastore service's underlying metadata store.</p></td>
<td><p><code dir="ltr" translate="no">metastore.  services.  queryMetadata</code></p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.metadataUser" class="role-title add-link" data-text="Dataproc Metastore Metadata User" tabindex="-1">Dataproc Metastore Metadata User</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.metadataUser</code> )</p>
<p>Access to the Dataproc Metastore gRPC endpoint</p></td>
<td><p><code dir="ltr" translate="no">metastore.databases.get</code></p>
<p><code dir="ltr" translate="no">metastore.databases.list</code></p>
<p><code dir="ltr" translate="no">metastore.services.get</code></p>
<p><code dir="ltr" translate="no">metastore.services.use</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.metadataViewer" class="role-title add-link" data-text="Dataproc Metastore Metadata Viewer" tabindex="-1">Dataproc Metastore Metadata Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.metadataViewer</code> )</p>
<p>Access to read the metadata of databases and tables under those databases</p></td>
<td><p><code dir="ltr" translate="no">metastore.databases.get</code></p>
<p><code dir="ltr" translate="no">metastore.  databases.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.databases.list</code></p>
<p><code dir="ltr" translate="no">metastore.services.get</code></p>
<p><code dir="ltr" translate="no">metastore.services.use</code></p>
<p><code dir="ltr" translate="no">metastore.tables.get</code></p>
<p><code dir="ltr" translate="no">metastore.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.tables.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.migrationAdmin" class="role-title add-link" data-text="Dataproc Metastore Managed Migration Admin" tabindex="-1">Dataproc Metastore Managed Migration Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p>
<p>Access to Dataproc Metastore Managed Migration resources and workflow.</p></td>
<td><p><code dir="ltr" translate="no">cloudsql.instances.connect</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.login</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.create</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.delete</code></p>
<p><code dir="ltr" translate="no">compute.disks.create</code></p>
<p><code dir="ltr" translate="no">compute.disks.delete</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.create</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.delete</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.use</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  use</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.delete</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.use</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  delete</code></p>
<p><code dir="ltr" translate="no">compute.instanceTemplates.get</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.instances.create</code></p>
<p><code dir="ltr" translate="no">compute.instances.delete</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.setMetadata</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  use</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  delete</code></p>
<p><code dir="ltr" translate="no">compute.regionHealthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  create</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  delete</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.zones.list</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  create</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  delete</code></p>
<p><code dir="ltr" translate="no">datastream.objects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastream.objects.get</code></li>
<li><code dir="ltr" translate="no">datastream.objects.list</code></li>
<li><code dir="ltr" translate="no">datastream.  objects.  startBackfillJob</code></li>
<li><code dir="ltr" translate="no">datastream.  objects.  stopBackfillJob</code></li>
</ul>
<p><code dir="ltr" translate="no">datastream.operations.get</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  create</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  delete</code></p>
<p><code dir="ltr" translate="no">datastream.streams.create</code></p>
<p><code dir="ltr" translate="no">datastream.streams.delete</code></p>
<p><code dir="ltr" translate="no">datastream.streams.get</code></p>
<p><code dir="ltr" translate="no">datastream.streams.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.user" class="role-title add-link" data-text="Dataproc Metastore Viewer" tabindex="-1">Dataproc Metastore Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.user</code> )</p>
<p>Read-only access to all Dataproc Metastore resources.</p></td>
<td><p><code dir="ltr" translate="no">metastore.backups.get</code></p>
<p><code dir="ltr" translate="no">metastore.backups.list</code></p>
<p><code dir="ltr" translate="no">metastore.federations.get</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.federations.list</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.imports.get</code></p>
<p><code dir="ltr" translate="no">metastore.imports.list</code></p>
<p><code dir="ltr" translate="no">metastore.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">metastore.locations.get</code></li>
<li><code dir="ltr" translate="no">metastore.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.operations.get</code></p>
<p><code dir="ltr" translate="no">metastore.operations.list</code></p>
<p><code dir="ltr" translate="no">metastore.services.export</code></p>
<p><code dir="ltr" translate="no">metastore.services.get</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.services.list</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="metastore.serviceAgent" class="role-title add-link" data-text="Dataproc Metastore Service Agent" tabindex="-1">Dataproc Metastore Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</p>
<p>Gives the Dataproc Metastore service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.use</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.create</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.delete</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.get</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  pscCreate</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  pscDelete</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.networks.addPeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">dns.changes.create</code></p>
<p><code dir="ltr" translate="no">dns.changes.get</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.create</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.delete</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.get</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSZone</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.create</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.delete</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.get</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.list</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">metastore.databases.get</code></p>
<p><code dir="ltr" translate="no">metastore.  databases.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.databases.update</code></p>
<p><code dir="ltr" translate="no">metastore.federations.use</code></p>
<p><code dir="ltr" translate="no">metastore.services.get</code></p>
<p><code dir="ltr" translate="no">metastore.tables.get</code></p>
<p><code dir="ltr" translate="no">metastore.tables.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.tables.update</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  delete</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  delete</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.delete</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Dataproc Metastore permissions

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
<td><h4 id="metastore.backups.create" class="permission-name add-link" data-text="metastore.backups.create" tabindex="-1"><code dir="ltr" translate="no">metastore.backups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.backups.delete" class="permission-name add-link" data-text="metastore.backups.delete" tabindex="-1"><code dir="ltr" translate="no">metastore.backups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.backups.get" class="permission-name add-link" data-text="metastore.backups.get" tabindex="-1"><code dir="ltr" translate="no">metastore.backups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.backups.getIamPolicy" class="permission-name add-link" data-text="metastore.backups.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">metastore.backups.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.backups.list" class="permission-name add-link" data-text="metastore.backups.list" tabindex="-1"><code dir="ltr" translate="no">metastore.backups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.backups.setIamPolicy" class="permission-name add-link" data-text="metastore.backups.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">metastore.backups.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.backups.use" class="permission-name add-link" data-text="metastore.backups.use" tabindex="-1"><code dir="ltr" translate="no">metastore.backups.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.databases.create" class="permission-name add-link" data-text="metastore.databases.create" tabindex="-1"><code dir="ltr" translate="no">metastore.databases.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.databases.delete" class="permission-name add-link" data-text="metastore.databases.delete" tabindex="-1"><code dir="ltr" translate="no">metastore.databases.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.databases.get" class="permission-name add-link" data-text="metastore.databases.get" tabindex="-1"><code dir="ltr" translate="no">metastore.databases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataUser">Dataproc Metastore Metadata User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.databases.getIamPolicy" class="permission-name add-link" data-text="metastore.databases.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">metastore.  databases.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.databases.list" class="permission-name add-link" data-text="metastore.databases.list" tabindex="-1"><code dir="ltr" translate="no">metastore.databases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataUser">Dataproc Metastore Metadata User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.databases.setIamPolicy" class="permission-name add-link" data-text="metastore.databases.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">metastore.  databases.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="metastore.databases.update" class="permission-name add-link" data-text="metastore.databases.update" tabindex="-1"><code dir="ltr" translate="no">metastore.databases.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.federations.create" class="permission-name add-link" data-text="metastore.federations.create" tabindex="-1"><code dir="ltr" translate="no">metastore.federations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.federations.createTagBinding" class="permission-name add-link" data-text="metastore.federations.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">metastore.  federations.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.federations.delete" class="permission-name add-link" data-text="metastore.federations.delete" tabindex="-1"><code dir="ltr" translate="no">metastore.federations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.federations.deleteTagBinding" class="permission-name add-link" data-text="metastore.federations.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">metastore.  federations.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.federations.get" class="permission-name add-link" data-text="metastore.federations.get" tabindex="-1"><code dir="ltr" translate="no">metastore.federations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.federations.getIamPolicy" class="permission-name add-link" data-text="metastore.federations.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">metastore.  federations.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.federations.list" class="permission-name add-link" data-text="metastore.federations.list" tabindex="-1"><code dir="ltr" translate="no">metastore.federations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.federations.listEffectiveTags" class="permission-name add-link" data-text="metastore.federations.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">metastore.  federations.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.federations.listTagBindings" class="permission-name add-link" data-text="metastore.federations.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">metastore.  federations.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.federations.setIamPolicy" class="permission-name add-link" data-text="metastore.federations.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">metastore.  federations.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.federations.update" class="permission-name add-link" data-text="metastore.federations.update" tabindex="-1"><code dir="ltr" translate="no">metastore.federations.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.federations.use" class="permission-name add-link" data-text="metastore.federations.use" tabindex="-1"><code dir="ltr" translate="no">metastore.federations.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.federationAccessor">Metastore Federation Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.federationAccessor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.imports.create" class="permission-name add-link" data-text="metastore.imports.create" tabindex="-1"><code dir="ltr" translate="no">metastore.imports.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.imports.get" class="permission-name add-link" data-text="metastore.imports.get" tabindex="-1"><code dir="ltr" translate="no">metastore.imports.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.imports.list" class="permission-name add-link" data-text="metastore.imports.list" tabindex="-1"><code dir="ltr" translate="no">metastore.imports.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.imports.update" class="permission-name add-link" data-text="metastore.imports.update" tabindex="-1"><code dir="ltr" translate="no">metastore.imports.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.locations.get" class="permission-name add-link" data-text="metastore.locations.get" tabindex="-1"><code dir="ltr" translate="no">metastore.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.locations.list" class="permission-name add-link" data-text="metastore.locations.list" tabindex="-1"><code dir="ltr" translate="no">metastore.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.migrations.cancel" class="permission-name add-link" data-text="metastore.migrations.cancel" tabindex="-1"><code dir="ltr" translate="no">metastore.migrations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.migrations.complete" class="permission-name add-link" data-text="metastore.migrations.complete" tabindex="-1"><code dir="ltr" translate="no">metastore.migrations.complete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.migrations.delete" class="permission-name add-link" data-text="metastore.migrations.delete" tabindex="-1"><code dir="ltr" translate="no">metastore.migrations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.migrations.get" class="permission-name add-link" data-text="metastore.migrations.get" tabindex="-1"><code dir="ltr" translate="no">metastore.migrations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.migrations.list" class="permission-name add-link" data-text="metastore.migrations.list" tabindex="-1"><code dir="ltr" translate="no">metastore.migrations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.migrations.start" class="permission-name add-link" data-text="metastore.migrations.start" tabindex="-1"><code dir="ltr" translate="no">metastore.migrations.start</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.operations.cancel" class="permission-name add-link" data-text="metastore.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">metastore.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.operations.delete" class="permission-name add-link" data-text="metastore.operations.delete" tabindex="-1"><code dir="ltr" translate="no">metastore.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.operations.get" class="permission-name add-link" data-text="metastore.operations.get" tabindex="-1"><code dir="ltr" translate="no">metastore.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.operations.list" class="permission-name add-link" data-text="metastore.operations.list" tabindex="-1"><code dir="ltr" translate="no">metastore.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.services.create" class="permission-name add-link" data-text="metastore.services.create" tabindex="-1"><code dir="ltr" translate="no">metastore.services.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.services.createTagBinding" class="permission-name add-link" data-text="metastore.services.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">metastore.  services.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.services.delete" class="permission-name add-link" data-text="metastore.services.delete" tabindex="-1"><code dir="ltr" translate="no">metastore.services.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.services.deleteTagBinding" class="permission-name add-link" data-text="metastore.services.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">metastore.  services.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.services.export" class="permission-name add-link" data-text="metastore.services.export" tabindex="-1"><code dir="ltr" translate="no">metastore.services.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.services.get" class="permission-name add-link" data-text="metastore.services.get" tabindex="-1"><code dir="ltr" translate="no">metastore.services.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataUser">Dataproc Metastore Metadata User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.services.getIamPolicy" class="permission-name add-link" data-text="metastore.services.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">metastore.  services.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.services.list" class="permission-name add-link" data-text="metastore.services.list" tabindex="-1"><code dir="ltr" translate="no">metastore.services.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.services.listEffectiveTags" class="permission-name add-link" data-text="metastore.services.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">metastore.  services.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.services.listTagBindings" class="permission-name add-link" data-text="metastore.services.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">metastore.  services.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.services.mutateMetadata" class="permission-name add-link" data-text="metastore.services.mutateMetadata" tabindex="-1"><code dir="ltr" translate="no">metastore.  services.  mutateMetadata</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataMutateAdmin">Dataproc Metastore Metadata Mutate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataMutateAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.services.queryMetadata" class="permission-name add-link" data-text="metastore.services.queryMetadata" tabindex="-1"><code dir="ltr" translate="no">metastore.  services.  queryMetadata</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataQueryAdmin">Dataproc Metastore Metadata Query Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataQueryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.services.restore" class="permission-name add-link" data-text="metastore.services.restore" tabindex="-1"><code dir="ltr" translate="no">metastore.services.restore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.services.setIamPolicy" class="permission-name add-link" data-text="metastore.services.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">metastore.  services.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.services.update" class="permission-name add-link" data-text="metastore.services.update" tabindex="-1"><code dir="ltr" translate="no">metastore.services.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.services.use" class="permission-name add-link" data-text="metastore.services.use" tabindex="-1"><code dir="ltr" translate="no">metastore.services.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataUser">Dataproc Metastore Metadata User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.tables.create" class="permission-name add-link" data-text="metastore.tables.create" tabindex="-1"><code dir="ltr" translate="no">metastore.tables.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.tables.delete" class="permission-name add-link" data-text="metastore.tables.delete" tabindex="-1"><code dir="ltr" translate="no">metastore.tables.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.tables.get" class="permission-name add-link" data-text="metastore.tables.get" tabindex="-1"><code dir="ltr" translate="no">metastore.tables.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="metastore.tables.getIamPolicy" class="permission-name add-link" data-text="metastore.tables.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">metastore.tables.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.tables.list" class="permission-name add-link" data-text="metastore.tables.list" tabindex="-1"><code dir="ltr" translate="no">metastore.tables.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="metastore.tables.setIamPolicy" class="permission-name add-link" data-text="metastore.tables.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">metastore.tables.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="metastore.tables.update" class="permission-name add-link" data-text="metastore.tables.update" tabindex="-1"><code dir="ltr" translate="no">metastore.tables.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
