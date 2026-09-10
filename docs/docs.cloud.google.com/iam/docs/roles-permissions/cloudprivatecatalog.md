---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog
title: Service Catalog roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Service Catalog. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Service Catalog roles

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
<td><h4 id="cloudprivatecatalog.admin" class="role-title add-link" data-text="Cloudprivatecatalog Admin Beta" tabindex="-1">Cloudprivatecatalog Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudprivatecatalog.admin</code> )</p>
<p>Admin role for cloudprivatecatalog</p></td>
<td><p><code dir="ltr" translate="no">cloudprivatecatalog.  targets.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalog.viewer" class="role-title add-link" data-text="Cloudprivatecatalog Viewer Beta" tabindex="-1">Cloudprivatecatalog Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudprivatecatalog.viewer</code> )</p>
<p>Viewer role for cloudprivatecatalog</p></td>
<td><p><code dir="ltr" translate="no">cloudprivatecatalog.  targets.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.admin" class="role-title add-link" data-text="Catalog Admin Beta" tabindex="-1">Catalog Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p>Can manage catalog and view its associations.</p></td>
<td><p><code dir="ltr" translate="no">cloudprivatecatalog.  targets.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  list</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  undelete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  attachProduct</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  detachProduct</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  list</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  list</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.  associate</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.  unassociate</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.editor" class="role-title add-link" data-text="Catalog Editor Beta" tabindex="-1">Catalog Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p>Editor role for Cloud Private Catalog</p></td>
<td><p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  create</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  delete</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  undelete</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  update</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  attachProduct</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  create</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  delete</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  detachProduct</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  update</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  create</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  delete</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  update</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  settings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  settings.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  settings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.  associate</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.  unassociate</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.viewer" class="role-title add-link" data-text="Catalog Viewer Beta" tabindex="-1">Catalog Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p>Viewer role for Cloud Private Catalog</p></td>
<td><p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  settings.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalog.consumer" class="role-title add-link" data-text="Catalog Consumer Beta" tabindex="-1">Catalog Consumer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudprivatecatalog.consumer</code> )</p>
<p>Can browse catalogs in the target resource context.</p></td>
<td><p><code dir="ltr" translate="no">cloudprivatecatalog.  targets.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.manager" class="role-title add-link" data-text="Catalog Manager Beta" tabindex="-1">Catalog Manager <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p>Can manage associations between a catalog and a target resource.</p></td>
<td><p><code dir="ltr" translate="no">cloudprivatecatalog.  targets.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.  associate</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.  unassociate</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.orgAdmin" class="role-title add-link" data-text="Catalog Org Admin Beta" tabindex="-1">Catalog Org Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p>Can manage catalog org settings.</p></td>
<td><p><code dir="ltr" translate="no">cloudprivatecatalog.  targets.  get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  list</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  list</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  list</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  undelete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  update</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  attachProduct</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  detachProduct</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  list</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  update</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  create</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  delete</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  list</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  update</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  settings.  get</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  settings.  update</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.  associate</code></li>
<li><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.  unassociate</code></li>
</ul>
<p><code dir="ltr" translate="no">commerceorggovernance.  organizationSettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceorggovernance.  organizationSettings.  get</code></li>
<li><code dir="ltr" translate="no">commerceorggovernance.  organizationSettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Service Catalog permissions

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
<td><h4 id="cloudprivatecatalog.targets.get" class="permission-name add-link" data-text="cloudprivatecatalog.targets.get" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalog.  targets.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.admin">Cloudprivatecatalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.viewer">Cloudprivatecatalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.consumer">Catalog Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalog.consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.associations.create" class="permission-name add-link" data-text="cloudprivatecatalogproducer.associations.create" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.associations.delete" class="permission-name add-link" data-text="cloudprivatecatalogproducer.associations.delete" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.associations.get" class="permission-name add-link" data-text="cloudprivatecatalogproducer.associations.get" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.associations.list" class="permission-name add-link" data-text="cloudprivatecatalogproducer.associations.list" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.catalogAssociations.create" class="permission-name add-link" data-text="cloudprivatecatalogproducer.catalogAssociations.create" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.catalogAssociations.delete" class="permission-name add-link" data-text="cloudprivatecatalogproducer.catalogAssociations.delete" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.catalogAssociations.get" class="permission-name add-link" data-text="cloudprivatecatalogproducer.catalogAssociations.get" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.catalogAssociations.list" class="permission-name add-link" data-text="cloudprivatecatalogproducer.catalogAssociations.list" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.catalogs.create" class="permission-name add-link" data-text="cloudprivatecatalogproducer.catalogs.create" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.catalogs.delete" class="permission-name add-link" data-text="cloudprivatecatalogproducer.catalogs.delete" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.catalogs.get" class="permission-name add-link" data-text="cloudprivatecatalogproducer.catalogs.get" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.catalogs.getIamPolicy" class="permission-name add-link" data-text="cloudprivatecatalogproducer.catalogs.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.catalogs.list" class="permission-name add-link" data-text="cloudprivatecatalogproducer.catalogs.list" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.catalogs.setIamPolicy" class="permission-name add-link" data-text="cloudprivatecatalogproducer.catalogs.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.catalogs.undelete" class="permission-name add-link" data-text="cloudprivatecatalogproducer.catalogs.undelete" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.catalogs.update" class="permission-name add-link" data-text="cloudprivatecatalogproducer.catalogs.update" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.producerCatalogs.attachProduct" class="permission-name add-link" data-text="cloudprivatecatalogproducer.producerCatalogs.attachProduct" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  attachProduct</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.producerCatalogs.create" class="permission-name add-link" data-text="cloudprivatecatalogproducer.producerCatalogs.create" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.producerCatalogs.delete" class="permission-name add-link" data-text="cloudprivatecatalogproducer.producerCatalogs.delete" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.producerCatalogs.detachProduct" class="permission-name add-link" data-text="cloudprivatecatalogproducer.producerCatalogs.detachProduct" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  detachProduct</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.producerCatalogs.get" class="permission-name add-link" data-text="cloudprivatecatalogproducer.producerCatalogs.get" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.producerCatalogs.getIamPolicy" class="permission-name add-link" data-text="cloudprivatecatalogproducer.producerCatalogs.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.producerCatalogs.list" class="permission-name add-link" data-text="cloudprivatecatalogproducer.producerCatalogs.list" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.producerCatalogs.setIamPolicy" class="permission-name add-link" data-text="cloudprivatecatalogproducer.producerCatalogs.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.producerCatalogs.update" class="permission-name add-link" data-text="cloudprivatecatalogproducer.producerCatalogs.update" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.products.create" class="permission-name add-link" data-text="cloudprivatecatalogproducer.products.create" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.products.delete" class="permission-name add-link" data-text="cloudprivatecatalogproducer.products.delete" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.products.get" class="permission-name add-link" data-text="cloudprivatecatalogproducer.products.get" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.products.getIamPolicy" class="permission-name add-link" data-text="cloudprivatecatalogproducer.products.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.products.list" class="permission-name add-link" data-text="cloudprivatecatalogproducer.products.list" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.products.setIamPolicy" class="permission-name add-link" data-text="cloudprivatecatalogproducer.products.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.products.update" class="permission-name add-link" data-text="cloudprivatecatalogproducer.products.update" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.settings.get" class="permission-name add-link" data-text="cloudprivatecatalogproducer.settings.get" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  settings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.settings.update" class="permission-name add-link" data-text="cloudprivatecatalogproducer.settings.update" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  settings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprivatecatalogproducer.targets.associate" class="permission-name add-link" data-text="cloudprivatecatalogproducer.targets.associate" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.  associate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprivatecatalogproducer.targets.unassociate" class="permission-name add-link" data-text="cloudprivatecatalogproducer.targets.unassociate" tabindex="-1"><code dir="ltr" translate="no">cloudprivatecatalogproducer.  targets.  unassociate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
</tbody>
</table>
