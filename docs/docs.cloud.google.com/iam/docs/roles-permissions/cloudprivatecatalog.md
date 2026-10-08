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
<td>Catalog Admin <sup>Beta</sup>
<p>( <code>roles/ cloudprivatecatalog.admin</code> )</p>
<p>Admin role for Cloud Private Catalog</p></td>
<td><p><code>cloudprivatecatalog. targets. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Catalog Viewer <sup>Beta</sup>
<p>( <code>roles/ cloudprivatecatalog.viewer</code> )</p>
<p>Viewer role for Cloud Private Catalog</p></td>
<td><p><code>cloudprivatecatalog. targets. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Catalog Admin <sup>Beta</sup>
<p>( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p>Can manage catalog and view its associations.</p></td>
<td><p><code>cloudprivatecatalog. targets. get</code></p>
<p><code>cloudprivatecatalogproducer. associations.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. associations. create</code></li>
<li><code>cloudprivatecatalogproducer. associations. delete</code></li>
<li><code>cloudprivatecatalogproducer. associations. get</code></li>
<li><code>cloudprivatecatalogproducer. associations. list</code></li>
</ul>
<p><code>cloudprivatecatalogproducer. catalogAssociations.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. catalogAssociations. create</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. delete</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. get</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. list</code></li>
</ul>
<p><code>cloudprivatecatalogproducer. catalogs.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. catalogs. create</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. delete</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. get</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. getIamPolicy</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. list</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. setIamPolicy</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. undelete</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. update</code></li>
</ul>
<p><code>cloudprivatecatalogproducer. producerCatalogs.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. producerCatalogs. attachProduct</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. create</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. delete</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. detachProduct</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. get</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. getIamPolicy</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. list</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. setIamPolicy</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. update</code></li>
</ul>
<p><code>cloudprivatecatalogproducer. products.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. products. create</code></li>
<li><code>cloudprivatecatalogproducer. products. delete</code></li>
<li><code>cloudprivatecatalogproducer. products. get</code></li>
<li><code>cloudprivatecatalogproducer. products. getIamPolicy</code></li>
<li><code>cloudprivatecatalogproducer. products. list</code></li>
<li><code>cloudprivatecatalogproducer. products. setIamPolicy</code></li>
<li><code>cloudprivatecatalogproducer. products. update</code></li>
</ul>
<p><code>cloudprivatecatalogproducer. targets.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. targets. associate</code></li>
<li><code>cloudprivatecatalogproducer. targets. unassociate</code></li>
</ul>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Catalog Editor <sup>Beta</sup>
<p>( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p>Editor role for Cloud Private Catalog</p></td>
<td><p><code>cloudprivatecatalogproducer. associations.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. associations. create</code></li>
<li><code>cloudprivatecatalogproducer. associations. delete</code></li>
<li><code>cloudprivatecatalogproducer. associations. get</code></li>
<li><code>cloudprivatecatalogproducer. associations. list</code></li>
</ul>
<p><code>cloudprivatecatalogproducer. catalogAssociations.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. catalogAssociations. create</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. delete</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. get</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. list</code></li>
</ul>
<p><code>cloudprivatecatalogproducer. catalogs. create</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. delete</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. get</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. getIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. list</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. undelete</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. update</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. attachProduct</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. create</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. delete</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. detachProduct</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. get</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. getIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. list</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. update</code></p>
<p><code>cloudprivatecatalogproducer. products. create</code></p>
<p><code>cloudprivatecatalogproducer. products. delete</code></p>
<p><code>cloudprivatecatalogproducer. products. get</code></p>
<p><code>cloudprivatecatalogproducer. products. getIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. products. list</code></p>
<p><code>cloudprivatecatalogproducer. products. update</code></p>
<p><code>cloudprivatecatalogproducer. settings.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. settings. get</code></li>
<li><code>cloudprivatecatalogproducer. settings. update</code></li>
</ul>
<p><code>cloudprivatecatalogproducer. targets.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. targets. associate</code></li>
<li><code>cloudprivatecatalogproducer. targets. unassociate</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Catalog Viewer <sup>Beta</sup>
<p>( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p>Viewer role for Cloud Private Catalog</p></td>
<td><p><code>cloudprivatecatalogproducer. associations. get</code></p>
<p><code>cloudprivatecatalogproducer. associations. list</code></p>
<p><code>cloudprivatecatalogproducer. catalogAssociations. get</code></p>
<p><code>cloudprivatecatalogproducer. catalogAssociations. list</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. get</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. getIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. list</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. get</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. getIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. list</code></p>
<p><code>cloudprivatecatalogproducer. products. get</code></p>
<p><code>cloudprivatecatalogproducer. products. getIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. products. list</code></p>
<p><code>cloudprivatecatalogproducer. settings. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Catalog Consumer <sup>Beta</sup>
<p>( <code>roles/ cloudprivatecatalog.consumer</code> )</p>
<p>Can browse catalogs in the target resource context.</p></td>
<td><p><code>cloudprivatecatalog. targets. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Catalog Manager <sup>Beta</sup>
<p>( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p>Can manage associations between a catalog and a target resource.</p></td>
<td><p><code>cloudprivatecatalog. targets. get</code></p>
<p><code>cloudprivatecatalogproducer. associations.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. associations. create</code></li>
<li><code>cloudprivatecatalogproducer. associations. delete</code></li>
<li><code>cloudprivatecatalogproducer. associations. get</code></li>
<li><code>cloudprivatecatalogproducer. associations. list</code></li>
</ul>
<p><code>cloudprivatecatalogproducer. catalogAssociations.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. catalogAssociations. create</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. delete</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. get</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. list</code></li>
</ul>
<p><code>cloudprivatecatalogproducer. catalogs. get</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. list</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. get</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. list</code></p>
<p><code>cloudprivatecatalogproducer. targets.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. targets. associate</code></li>
<li><code>cloudprivatecatalogproducer. targets. unassociate</code></li>
</ul>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Catalog Org Admin <sup>Beta</sup>
<p>( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p>Can manage catalog org settings.</p></td>
<td><p><code>cloudprivatecatalog. targets. get</code></p>
<p><code>cloudprivatecatalogproducer.*</code></p>
<ul>
<li><code>cloudprivatecatalogproducer. associations. create</code></li>
<li><code>cloudprivatecatalogproducer. associations. delete</code></li>
<li><code>cloudprivatecatalogproducer. associations. get</code></li>
<li><code>cloudprivatecatalogproducer. associations. list</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. create</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. delete</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. get</code></li>
<li><code>cloudprivatecatalogproducer. catalogAssociations. list</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. create</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. delete</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. get</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. getIamPolicy</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. list</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. setIamPolicy</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. undelete</code></li>
<li><code>cloudprivatecatalogproducer. catalogs. update</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. attachProduct</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. create</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. delete</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. detachProduct</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. get</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. getIamPolicy</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. list</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. setIamPolicy</code></li>
<li><code>cloudprivatecatalogproducer. producerCatalogs. update</code></li>
<li><code>cloudprivatecatalogproducer. products. create</code></li>
<li><code>cloudprivatecatalogproducer. products. delete</code></li>
<li><code>cloudprivatecatalogproducer. products. get</code></li>
<li><code>cloudprivatecatalogproducer. products. getIamPolicy</code></li>
<li><code>cloudprivatecatalogproducer. products. list</code></li>
<li><code>cloudprivatecatalogproducer. products. setIamPolicy</code></li>
<li><code>cloudprivatecatalogproducer. products. update</code></li>
<li><code>cloudprivatecatalogproducer. settings. get</code></li>
<li><code>cloudprivatecatalogproducer. settings. update</code></li>
<li><code>cloudprivatecatalogproducer. targets. associate</code></li>
<li><code>cloudprivatecatalogproducer. targets. unassociate</code></li>
</ul>
<p><code>commerceorggovernance. organizationSettings.*</code></p>
<ul>
<li><code>commerceorggovernance. organizationSettings. get</code></li>
<li><code>commerceorggovernance. organizationSettings. update</code></li>
</ul>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td><code>cloudprivatecatalog. targets. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.consumer">Catalog Consumer</a> ( <code>roles/ cloudprivatecatalog.consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. associations. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. associations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. associations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. associations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. catalogAssociations. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. catalogAssociations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. catalogAssociations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. catalogAssociations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. catalogs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. catalogs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. catalogs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. catalogs. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. catalogs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. catalogs. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. catalogs. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. catalogs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. producerCatalogs. attachProduct</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. producerCatalogs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. producerCatalogs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. producerCatalogs. detachProduct</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. producerCatalogs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. producerCatalogs. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. producerCatalogs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. producerCatalogs. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. producerCatalogs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. products. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. products. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. products. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. products. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. products. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. products. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. products. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. settings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. settings. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudprivatecatalogproducer. targets. associate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudprivatecatalogproducer. targets. unassociate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p></td>
</tr>
</tbody>
</table>
