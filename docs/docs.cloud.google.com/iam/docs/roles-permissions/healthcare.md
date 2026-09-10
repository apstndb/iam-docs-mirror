---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/healthcare
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare
title: Cloud Healthcare API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Healthcare API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Healthcare API roles

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
<td><h4 id="healthcare.annotationEditor" class="role-title add-link" data-text="Healthcare Annotation Editor" tabindex="-1">Healthcare Annotation Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p>
<p>Create, delete, update, read and list annotations.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.  annotationStores.  get</code></p>
<p><code dir="ltr" translate="no">healthcare.  annotationStores.  list</code></p>
<p><code dir="ltr" translate="no">healthcare.annotations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.annotations.create</code></li>
<li><code dir="ltr" translate="no">healthcare.annotations.delete</code></li>
<li><code dir="ltr" translate="no">healthcare.annotations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.annotations.list</code></li>
<li><code dir="ltr" translate="no">healthcare.annotations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.annotationReader" class="role-title add-link" data-text="Healthcare Annotation Reader" tabindex="-1">Healthcare Annotation Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.annotationReader</code> )</p>
<p>Read and list annotations in an Annotation store.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.  annotationStores.  get</code></p>
<p><code dir="ltr" translate="no">healthcare.  annotationStores.  list</code></p>
<p><code dir="ltr" translate="no">healthcare.annotations.get</code></p>
<p><code dir="ltr" translate="no">healthcare.annotations.list</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.annotationStoreAdmin" class="role-title add-link" data-text="Healthcare Annotation Administrator" tabindex="-1">Healthcare Annotation Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p>Administer Annotation stores.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.annotationStores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.  annotationStores.  create</code></li>
<li><code dir="ltr" translate="no">healthcare.  annotationStores.  delete</code></li>
<li><code dir="ltr" translate="no">healthcare.  annotationStores.  evaluate</code></li>
<li><code dir="ltr" translate="no">healthcare.  annotationStores.  export</code></li>
<li><code dir="ltr" translate="no">healthcare.  annotationStores.  get</code></li>
<li><code dir="ltr" translate="no">healthcare.  annotationStores.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">healthcare.  annotationStores.  import</code></li>
<li><code dir="ltr" translate="no">healthcare.  annotationStores.  list</code></li>
<li><code dir="ltr" translate="no">healthcare.  annotationStores.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">healthcare.  annotationStores.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.annotationStoreViewer" class="role-title add-link" data-text="Healthcare Annotation Store Viewer" tabindex="-1">Healthcare Annotation Store Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.annotationStoreViewer</code> )</p>
<p>List Annotation Stores in a dataset.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.  annotationStores.  get</code></p>
<p><code dir="ltr" translate="no">healthcare.  annotationStores.  list</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.attributeDefinitionEditor" class="role-title add-link" data-text="Healthcare Attribute Definition Editor" tabindex="-1">Healthcare Attribute Definition Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p>Edit AttributeDefinition objects.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.  attributeDefinitions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  create</code></li>
<li><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  delete</code></li>
<li><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  get</code></li>
<li><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  list</code></li>
<li><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  checkDataAccess</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  evaluateUserConsents</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  queryAccessibleData</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.attributeDefinitionReader" class="role-title add-link" data-text="Healthcare Attribute Definition Reader" tabindex="-1">Healthcare Attribute Definition Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p>Read AttributeDefinition objects in a consent store.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  get</code></p>
<p><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  checkDataAccess</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  evaluateUserConsents</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  queryAccessibleData</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consentArtifactAdmin" class="role-title add-link" data-text="Healthcare Consent Artifact Administrator" tabindex="-1">Healthcare Consent Artifact Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p>Administer ConsentArtifact objects.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.consentArtifacts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.  consentArtifacts.  create</code></li>
<li><code dir="ltr" translate="no">healthcare.  consentArtifacts.  delete</code></li>
<li><code dir="ltr" translate="no">healthcare.  consentArtifacts.  get</code></li>
<li><code dir="ltr" translate="no">healthcare.  consentArtifacts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  checkDataAccess</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  evaluateUserConsents</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  queryAccessibleData</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consentArtifactEditor" class="role-title add-link" data-text="Healthcare Consent Artifact Editor" tabindex="-1">Healthcare Consent Artifact Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p>Edit ConsentArtifact objects.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.  consentArtifacts.  create</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentArtifacts.  get</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentArtifacts.  list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  checkDataAccess</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  evaluateUserConsents</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  queryAccessibleData</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consentArtifactReader" class="role-title add-link" data-text="Healthcare Consent Artifact Reader" tabindex="-1">Healthcare Consent Artifact Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p>Read ConsentArtifact objects in a consent store.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.  consentArtifacts.  get</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentArtifacts.  list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  checkDataAccess</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  evaluateUserConsents</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  queryAccessibleData</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consentEditor" class="role-title add-link" data-text="Healthcare Consent Editor" tabindex="-1">Healthcare Consent Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p>Edit Consent objects.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.  consentStores.  checkDataAccess</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  evaluateUserConsents</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  queryAccessibleData</code></p>
<p><code dir="ltr" translate="no">healthcare.consents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.consents.activate</code></li>
<li><code dir="ltr" translate="no">healthcare.consents.create</code></li>
<li><code dir="ltr" translate="no">healthcare.consents.delete</code></li>
<li><code dir="ltr" translate="no">healthcare.consents.get</code></li>
<li><code dir="ltr" translate="no">healthcare.consents.list</code></li>
<li><code dir="ltr" translate="no">healthcare.consents.reject</code></li>
<li><code dir="ltr" translate="no">healthcare.consents.revoke</code></li>
<li><code dir="ltr" translate="no">healthcare.consents.update</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consentReader" class="role-title add-link" data-text="Healthcare Consent Reader" tabindex="-1">Healthcare Consent Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p>Read Consent objects in a consent store.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.  consentStores.  checkDataAccess</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  evaluateUserConsents</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  queryAccessibleData</code></p>
<p><code dir="ltr" translate="no">healthcare.consents.get</code></p>
<p><code dir="ltr" translate="no">healthcare.consents.list</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consentStoreAdmin" class="role-title add-link" data-text="Healthcare Consent Store Administrator" tabindex="-1">Healthcare Consent Store Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p>Administer Consent stores.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.consentStores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.  consentStores.  checkDataAccess</code></li>
<li><code dir="ltr" translate="no">healthcare.  consentStores.  create</code></li>
<li><code dir="ltr" translate="no">healthcare.  consentStores.  delete</code></li>
<li><code dir="ltr" translate="no">healthcare.  consentStores.  evaluateUserConsents</code></li>
<li><code dir="ltr" translate="no">healthcare.consentStores.get</code></li>
<li><code dir="ltr" translate="no">healthcare.  consentStores.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">healthcare.consentStores.list</code></li>
<li><code dir="ltr" translate="no">healthcare.  consentStores.  queryAccessibleData</code></li>
<li><code dir="ltr" translate="no">healthcare.  consentStores.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">healthcare.  consentStores.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consentStoreViewer" class="role-title add-link" data-text="Healthcare Consent Store Viewer" tabindex="-1">Healthcare Consent Store Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p>List Consent Stores in a dataset.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.  consentStores.  checkDataAccess</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  evaluateUserConsents</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  queryAccessibleData</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.datasetAdmin" class="role-title add-link" data-text="Healthcare Dataset Administrator" tabindex="-1">Healthcare Dataset Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p>
<p>Administer Healthcare Datasets.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.datasets.create</code></li>
<li><code dir="ltr" translate="no">healthcare.datasets.deidentify</code></li>
<li><code dir="ltr" translate="no">healthcare.datasets.delete</code></li>
<li><code dir="ltr" translate="no">healthcare.datasets.get</code></li>
<li><code dir="ltr" translate="no">healthcare.  datasets.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">healthcare.datasets.list</code></li>
<li><code dir="ltr" translate="no">healthcare.  datasets.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">healthcare.datasets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.operations.cancel</code></li>
<li><code dir="ltr" translate="no">healthcare.operations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.datasetViewer" class="role-title add-link" data-text="Healthcare Dataset Viewer" tabindex="-1">Healthcare Dataset Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.datasetViewer</code> )</p>
<p>List the Healthcare Datasets in a project.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.dicomEditor" class="role-title add-link" data-text="Healthcare DICOM Editor" tabindex="-1">Healthcare DICOM Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p>Edit DICOM images individually and in bulk.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  dicomStores.  dicomWebDelete</code></p>
<p><code dir="ltr" translate="no">healthcare.  dicomStores.  dicomWebRead</code></p>
<p><code dir="ltr" translate="no">healthcare.  dicomStores.  dicomWebUpdate</code></p>
<p><code dir="ltr" translate="no">healthcare.  dicomStores.  dicomWebWrite</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.export</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.import</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.cancel</code></p>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.dicomStoreAdmin" class="role-title add-link" data-text="Healthcare DICOM Store Administrator" tabindex="-1">Healthcare DICOM Store Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p>
<p>Administer DICOM stores.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.create</code></p>
<p><code dir="ltr" translate="no">healthcare.  dicomStores.  deidentify</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.delete</code></p>
<p><code dir="ltr" translate="no">healthcare.  dicomStores.  dicomWebDelete</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.  dicomStores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  dicomStores.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.update</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.cancel</code></p>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.dicomStoreViewer" class="role-title add-link" data-text="Healthcare DICOM Store Viewer" tabindex="-1">Healthcare DICOM Store Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.dicomStoreViewer</code> )</p>
<p>List DICOM Stores in a dataset.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.dicomViewer" class="role-title add-link" data-text="Healthcare DICOM Viewer" tabindex="-1">Healthcare DICOM Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.dicomViewer</code> )</p>
<p>Retrieve DICOM images from a DICOM store.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  dicomStores.  dicomWebRead</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.export</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirResourceEditor" class="role-title add-link" data-text="Healthcare FHIR Resource Editor" tabindex="-1">Healthcare FHIR Resource Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p>Create, delete, update, read and search FHIR resources.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirResources.  create</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirResources.  delete</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirResources.get</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirResources.patch</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirResources.  translateConceptMap</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirResources.  update</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  executeBundle</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  searchResources</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.cancel</code></p>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirResourceReader" class="role-title add-link" data-text="Healthcare FHIR Resource Reader" tabindex="-1">Healthcare FHIR Resource Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p>Read and search FHIR resources.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirResources.get</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirResources.  translateConceptMap</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  executeBundle</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  searchResources</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirStoreAdmin" class="role-title add-link" data-text="Healthcare FHIR Store Administrator" tabindex="-1">Healthcare FHIR Store Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p>Administer FHIR resource stores.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirResources.purge</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  applyConsents</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  bulkDelete</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  configureSearch</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.create</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  deidentify</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.delete</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  deleteFhirOperation</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  explainDataAccess</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.export</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  getFhirOperation</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.import</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.rollback</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.update</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.cancel</code></p>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirStoreViewer" class="role-title add-link" data-text="Healthcare FHIR Store Viewer" tabindex="-1">Healthcare FHIR Store Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.fhirStoreViewer</code> )</p>
<p>List FHIR Stores in a dataset.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.hl7V2Consumer" class="role-title add-link" data-text="Healthcare HL7v2 Message Consumer" tabindex="-1">Healthcare HL7v2 Message Consumer</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p>List and read HL7v2 messages, update message labels, and publish new messages.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  hl7V2Messages.  create</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Messages.get</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Messages.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  hl7V2Messages.  update</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Stores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Stores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.hl7V2Editor" class="role-title add-link" data-text="Healthcare HL7v2 Message Editor" tabindex="-1">Healthcare HL7v2 Message Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p>Read, write, and delete access to HL7v2 messages.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Messages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.  hl7V2Messages.  create</code></li>
<li><code dir="ltr" translate="no">healthcare.  hl7V2Messages.  delete</code></li>
<li><code dir="ltr" translate="no">healthcare.hl7V2Messages.get</code></li>
<li><code dir="ltr" translate="no">healthcare.  hl7V2Messages.  ingest</code></li>
<li><code dir="ltr" translate="no">healthcare.hl7V2Messages.list</code></li>
<li><code dir="ltr" translate="no">healthcare.  hl7V2Messages.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.hl7V2Stores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Stores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.cancel</code></p>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.hl7V2Ingest" class="role-title add-link" data-text="Healthcare HL7v2 Message Ingest" tabindex="-1">Healthcare HL7v2 Message Ingest</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.hl7V2Ingest</code> )</p>
<p>Ingest HL7v2 messages received from a source network.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  hl7V2Messages.  ingest</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Stores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Stores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.hl7V2StoreAdmin" class="role-title add-link" data-text="Healthcare HL7v2 Store Administrator" tabindex="-1">Healthcare HL7v2 Store Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p>
<p>Administer HL7v2 Stores.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Stores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.hl7V2Stores.create</code></li>
<li><code dir="ltr" translate="no">healthcare.hl7V2Stores.delete</code></li>
<li><code dir="ltr" translate="no">healthcare.hl7V2Stores.export</code></li>
<li><code dir="ltr" translate="no">healthcare.hl7V2Stores.get</code></li>
<li><code dir="ltr" translate="no">healthcare.  hl7V2Stores.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">healthcare.hl7V2Stores.import</code></li>
<li><code dir="ltr" translate="no">healthcare.hl7V2Stores.list</code></li>
<li><code dir="ltr" translate="no">healthcare.  hl7V2Stores.  rollback</code></li>
<li><code dir="ltr" translate="no">healthcare.  hl7V2Stores.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">healthcare.hl7V2Stores.update</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.cancel</code></p>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.hl7V2StoreViewer" class="role-title add-link" data-text="Healthcare HL7v2 Store Viewer" tabindex="-1">Healthcare HL7v2 Store Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.hl7V2StoreViewer</code> )</p>
<p>View HL7v2 Stores in a dataset.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Stores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Stores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.nlpServiceViewer" class="role-title add-link" data-text="Healthcare NLP Service Viewer Beta" tabindex="-1">Healthcare NLP Service Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.nlpServiceViewer</code> )</p>
<p>Extract and analyze medical entities from a given text.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.  nlpservice.  analyzeEntities</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.userDataMappingEditor" class="role-title add-link" data-text="Healthcare User Data Mapping Editor" tabindex="-1">Healthcare User Data Mapping Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p>Edit UserDataMapping objects.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.  consentStores.  checkDataAccess</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  evaluateUserConsents</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  queryAccessibleData</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">healthcare.userDataMappings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.  userDataMappings.  archive</code></li>
<li><code dir="ltr" translate="no">healthcare.  userDataMappings.  create</code></li>
<li><code dir="ltr" translate="no">healthcare.  userDataMappings.  delete</code></li>
<li><code dir="ltr" translate="no">healthcare.  userDataMappings.  get</code></li>
<li><code dir="ltr" translate="no">healthcare.  userDataMappings.  list</code></li>
<li><code dir="ltr" translate="no">healthcare.  userDataMappings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.userDataMappingReader" class="role-title add-link" data-text="Healthcare User Data Mapping Reader" tabindex="-1">Healthcare User Data Mapping Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p>Read UserDataMapping objects in a consent store.</p></td>
<td><p><code dir="ltr" translate="no">healthcare.  consentStores.  checkDataAccess</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  evaluateUserConsents</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.get</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  queryAccessibleData</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.get</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">healthcare.locations.get</code></li>
<li><code dir="ltr" translate="no">healthcare.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">healthcare.operations.get</code></p>
<p><code dir="ltr" translate="no">healthcare.  userDataMappings.  get</code></p>
<p><code dir="ltr" translate="no">healthcare.  userDataMappings.  list</code></p>
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
<td><h4 id="healthcare.serviceAgent" class="role-title add-link" data-text="Healthcare Service Agent" tabindex="-1">Healthcare Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  healthcare.serviceAgent</code> )</p>
<p>Gives the Healthcare Service Account access to networks, Kubernetes engine, and Pub/Sub resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.get</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.alerts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.alerts.get</code></li>
<li><code dir="ltr" translate="no">monitoring.alerts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.dashboards.get</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.groups.get</code></p>
<p><code dir="ltr" translate="no">monitoring.groups.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.  notificationChannelDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  notificationChannelDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  notificationChannelDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.  notificationChannels.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  notificationChannels.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.services.get</code></p>
<p><code dir="ltr" translate="no">monitoring.services.list</code></p>
<p><code dir="ltr" translate="no">monitoring.slos.get</code></p>
<p><code dir="ltr" translate="no">monitoring.slos.list</code></p>
<p><code dir="ltr" translate="no">monitoring.snoozes.get</code></p>
<p><code dir="ltr" translate="no">monitoring.snoozes.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.timeSeries.create</code></li>
<li><code dir="ltr" translate="no">monitoring.timeSeries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  list</code></p>
<p><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  list</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.seek</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p>
<p><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  list</code></p></td>
</tr>
</tbody>
</table>

## Cloud Healthcare API permissions

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
<td><h4 id="healthcare.annotationStores.create" class="permission-name add-link" data-text="healthcare.annotationStores.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.  annotationStores.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.annotationStores.delete" class="permission-name add-link" data-text="healthcare.annotationStores.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.  annotationStores.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.annotationStores.evaluate" class="permission-name add-link" data-text="healthcare.annotationStores.evaluate" tabindex="-1"><code dir="ltr" translate="no">healthcare.  annotationStores.  evaluate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.annotationStores.export" class="permission-name add-link" data-text="healthcare.annotationStores.export" tabindex="-1"><code dir="ltr" translate="no">healthcare.  annotationStores.  export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.annotationStores.get" class="permission-name add-link" data-text="healthcare.annotationStores.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.  annotationStores.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreViewer">Healthcare Annotation Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.annotationStores.getIamPolicy" class="permission-name add-link" data-text="healthcare.annotationStores.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">healthcare.  annotationStores.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.annotationStores.import" class="permission-name add-link" data-text="healthcare.annotationStores.import" tabindex="-1"><code dir="ltr" translate="no">healthcare.  annotationStores.  import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.annotationStores.list" class="permission-name add-link" data-text="healthcare.annotationStores.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.  annotationStores.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreViewer">Healthcare Annotation Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.annotationStores.setIamPolicy" class="permission-name add-link" data-text="healthcare.annotationStores.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">healthcare.  annotationStores.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.annotationStores.update" class="permission-name add-link" data-text="healthcare.annotationStores.update" tabindex="-1"><code dir="ltr" translate="no">healthcare.  annotationStores.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.annotations.create" class="permission-name add-link" data-text="healthcare.annotations.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.annotations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.annotations.delete" class="permission-name add-link" data-text="healthcare.annotations.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.annotations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.annotations.get" class="permission-name add-link" data-text="healthcare.annotations.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.annotations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.annotations.list" class="permission-name add-link" data-text="healthcare.annotations.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.annotations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.annotations.update" class="permission-name add-link" data-text="healthcare.annotations.update" tabindex="-1"><code dir="ltr" translate="no">healthcare.annotations.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.attributeDefinitions.create" class="permission-name add-link" data-text="healthcare.attributeDefinitions.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.attributeDefinitions.delete" class="permission-name add-link" data-text="healthcare.attributeDefinitions.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.attributeDefinitions.get" class="permission-name add-link" data-text="healthcare.attributeDefinitions.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.attributeDefinitions.list" class="permission-name add-link" data-text="healthcare.attributeDefinitions.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.attributeDefinitions.update" class="permission-name add-link" data-text="healthcare.attributeDefinitions.update" tabindex="-1"><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consentArtifacts.create" class="permission-name add-link" data-text="healthcare.consentArtifacts.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.  consentArtifacts.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consentArtifacts.delete" class="permission-name add-link" data-text="healthcare.consentArtifacts.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.  consentArtifacts.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consentArtifacts.get" class="permission-name add-link" data-text="healthcare.consentArtifacts.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.  consentArtifacts.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consentArtifacts.list" class="permission-name add-link" data-text="healthcare.consentArtifacts.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.  consentArtifacts.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consentStores.checkDataAccess" class="permission-name add-link" data-text="healthcare.consentStores.checkDataAccess" tabindex="-1"><code dir="ltr" translate="no">healthcare.  consentStores.  checkDataAccess</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consentStores.create" class="permission-name add-link" data-text="healthcare.consentStores.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.  consentStores.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consentStores.delete" class="permission-name add-link" data-text="healthcare.consentStores.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.  consentStores.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consentStores.evaluateUserConsents" class="permission-name add-link" data-text="healthcare.consentStores.evaluateUserConsents" tabindex="-1"><code dir="ltr" translate="no">healthcare.  consentStores.  evaluateUserConsents</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consentStores.get" class="permission-name add-link" data-text="healthcare.consentStores.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.consentStores.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consentStores.getIamPolicy" class="permission-name add-link" data-text="healthcare.consentStores.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">healthcare.  consentStores.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consentStores.list" class="permission-name add-link" data-text="healthcare.consentStores.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.consentStores.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consentStores.queryAccessibleData" class="permission-name add-link" data-text="healthcare.consentStores.queryAccessibleData" tabindex="-1"><code dir="ltr" translate="no">healthcare.  consentStores.  queryAccessibleData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consentStores.setIamPolicy" class="permission-name add-link" data-text="healthcare.consentStores.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">healthcare.  consentStores.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consentStores.update" class="permission-name add-link" data-text="healthcare.consentStores.update" tabindex="-1"><code dir="ltr" translate="no">healthcare.  consentStores.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consents.activate" class="permission-name add-link" data-text="healthcare.consents.activate" tabindex="-1"><code dir="ltr" translate="no">healthcare.consents.activate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consents.create" class="permission-name add-link" data-text="healthcare.consents.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.consents.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consents.delete" class="permission-name add-link" data-text="healthcare.consents.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.consents.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consents.get" class="permission-name add-link" data-text="healthcare.consents.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.consents.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consents.list" class="permission-name add-link" data-text="healthcare.consents.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.consents.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consents.reject" class="permission-name add-link" data-text="healthcare.consents.reject" tabindex="-1"><code dir="ltr" translate="no">healthcare.consents.reject</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.consents.revoke" class="permission-name add-link" data-text="healthcare.consents.revoke" tabindex="-1"><code dir="ltr" translate="no">healthcare.consents.revoke</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.consents.update" class="permission-name add-link" data-text="healthcare.consents.update" tabindex="-1"><code dir="ltr" translate="no">healthcare.consents.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.datasets.create" class="permission-name add-link" data-text="healthcare.datasets.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.datasets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.datasets.deidentify" class="permission-name add-link" data-text="healthcare.datasets.deidentify" tabindex="-1"><code dir="ltr" translate="no">healthcare.datasets.deidentify</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.datasets.delete" class="permission-name add-link" data-text="healthcare.datasets.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.datasets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.datasets.get" class="permission-name add-link" data-text="healthcare.datasets.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.datasets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreViewer">Healthcare Annotation Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetViewer">Healthcare Dataset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreViewer">Healthcare DICOM Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreViewer">Healthcare FHIR Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Ingest">Healthcare HL7v2 Message Ingest</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Ingest</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreViewer">Healthcare HL7v2 Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.datasets.getIamPolicy" class="permission-name add-link" data-text="healthcare.datasets.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">healthcare.  datasets.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.datasets.list" class="permission-name add-link" data-text="healthcare.datasets.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.datasets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreViewer">Healthcare Annotation Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetViewer">Healthcare Dataset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreViewer">Healthcare DICOM Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreViewer">Healthcare FHIR Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Ingest">Healthcare HL7v2 Message Ingest</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Ingest</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreViewer">Healthcare HL7v2 Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.datasets.setIamPolicy" class="permission-name add-link" data-text="healthcare.datasets.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">healthcare.  datasets.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.datasets.update" class="permission-name add-link" data-text="healthcare.datasets.update" tabindex="-1"><code dir="ltr" translate="no">healthcare.datasets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.dicomStores.create" class="permission-name add-link" data-text="healthcare.dicomStores.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.dicomStores.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.dicomStores.deidentify" class="permission-name add-link" data-text="healthcare.dicomStores.deidentify" tabindex="-1"><code dir="ltr" translate="no">healthcare.  dicomStores.  deidentify</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.dicomStores.delete" class="permission-name add-link" data-text="healthcare.dicomStores.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.dicomStores.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.dicomStores.dicomWebDelete" class="permission-name add-link" data-text="healthcare.dicomStores.dicomWebDelete" tabindex="-1"><code dir="ltr" translate="no">healthcare.  dicomStores.  dicomWebDelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.dicomStores.dicomWebRead" class="permission-name add-link" data-text="healthcare.dicomStores.dicomWebRead" tabindex="-1"><code dir="ltr" translate="no">healthcare.  dicomStores.  dicomWebRead</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.dicomStores.dicomWebUpdate" class="permission-name add-link" data-text="healthcare.dicomStores.dicomWebUpdate" tabindex="-1"><code dir="ltr" translate="no">healthcare.  dicomStores.  dicomWebUpdate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.dicomStores.dicomWebWrite" class="permission-name add-link" data-text="healthcare.dicomStores.dicomWebWrite" tabindex="-1"><code dir="ltr" translate="no">healthcare.  dicomStores.  dicomWebWrite</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.dicomStores.export" class="permission-name add-link" data-text="healthcare.dicomStores.export" tabindex="-1"><code dir="ltr" translate="no">healthcare.dicomStores.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.dicomStores.get" class="permission-name add-link" data-text="healthcare.dicomStores.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.dicomStores.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreViewer">Healthcare DICOM Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.dicomStores.getIamPolicy" class="permission-name add-link" data-text="healthcare.dicomStores.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">healthcare.  dicomStores.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.dicomStores.import" class="permission-name add-link" data-text="healthcare.dicomStores.import" tabindex="-1"><code dir="ltr" translate="no">healthcare.dicomStores.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.dicomStores.list" class="permission-name add-link" data-text="healthcare.dicomStores.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.dicomStores.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreViewer">Healthcare DICOM Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.dicomStores.setIamPolicy" class="permission-name add-link" data-text="healthcare.dicomStores.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">healthcare.  dicomStores.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.dicomStores.update" class="permission-name add-link" data-text="healthcare.dicomStores.update" tabindex="-1"><code dir="ltr" translate="no">healthcare.dicomStores.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirResources.create" class="permission-name add-link" data-text="healthcare.fhirResources.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirResources.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirResources.delete" class="permission-name add-link" data-text="healthcare.fhirResources.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirResources.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirResources.get" class="permission-name add-link" data-text="healthcare.fhirResources.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.fhirResources.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirResources.patch" class="permission-name add-link" data-text="healthcare.fhirResources.patch" tabindex="-1"><code dir="ltr" translate="no">healthcare.fhirResources.patch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirResources.purge" class="permission-name add-link" data-text="healthcare.fhirResources.purge" tabindex="-1"><code dir="ltr" translate="no">healthcare.fhirResources.purge</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirResources.translateConceptMap" class="permission-name add-link" data-text="healthcare.fhirResources.translateConceptMap" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirResources.  translateConceptMap</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirResources.update" class="permission-name add-link" data-text="healthcare.fhirResources.update" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirResources.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirStores.applyConsents" class="permission-name add-link" data-text="healthcare.fhirStores.applyConsents" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirStores.  applyConsents</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirStores.bulkDelete" class="permission-name add-link" data-text="healthcare.fhirStores.bulkDelete" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirStores.  bulkDelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirStores.configureSearch" class="permission-name add-link" data-text="healthcare.fhirStores.configureSearch" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirStores.  configureSearch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirStores.create" class="permission-name add-link" data-text="healthcare.fhirStores.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.fhirStores.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirStores.deidentify" class="permission-name add-link" data-text="healthcare.fhirStores.deidentify" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirStores.  deidentify</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirStores.delete" class="permission-name add-link" data-text="healthcare.fhirStores.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.fhirStores.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirStores.deleteFhirOperation" class="permission-name add-link" data-text="healthcare.fhirStores.deleteFhirOperation" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirStores.  deleteFhirOperation</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirStores.executeBundle" class="permission-name add-link" data-text="healthcare.fhirStores.executeBundle" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirStores.  executeBundle</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirStores.explainDataAccess" class="permission-name add-link" data-text="healthcare.fhirStores.explainDataAccess" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirStores.  explainDataAccess</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirStores.export" class="permission-name add-link" data-text="healthcare.fhirStores.export" tabindex="-1"><code dir="ltr" translate="no">healthcare.fhirStores.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirStores.get" class="permission-name add-link" data-text="healthcare.fhirStores.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.fhirStores.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreViewer">Healthcare FHIR Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirStores.getFhirOperation" class="permission-name add-link" data-text="healthcare.fhirStores.getFhirOperation" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirStores.  getFhirOperation</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirStores.getIamPolicy" class="permission-name add-link" data-text="healthcare.fhirStores.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirStores.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirStores.import" class="permission-name add-link" data-text="healthcare.fhirStores.import" tabindex="-1"><code dir="ltr" translate="no">healthcare.fhirStores.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirStores.list" class="permission-name add-link" data-text="healthcare.fhirStores.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.fhirStores.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreViewer">Healthcare FHIR Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirStores.rollback" class="permission-name add-link" data-text="healthcare.fhirStores.rollback" tabindex="-1"><code dir="ltr" translate="no">healthcare.fhirStores.rollback</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirStores.searchResources" class="permission-name add-link" data-text="healthcare.fhirStores.searchResources" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirStores.  searchResources</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.fhirStores.setIamPolicy" class="permission-name add-link" data-text="healthcare.fhirStores.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">healthcare.  fhirStores.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.fhirStores.update" class="permission-name add-link" data-text="healthcare.fhirStores.update" tabindex="-1"><code dir="ltr" translate="no">healthcare.fhirStores.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.hl7V2Messages.create" class="permission-name add-link" data-text="healthcare.hl7V2Messages.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.  hl7V2Messages.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.hl7V2Messages.delete" class="permission-name add-link" data-text="healthcare.hl7V2Messages.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.  hl7V2Messages.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.hl7V2Messages.get" class="permission-name add-link" data-text="healthcare.hl7V2Messages.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.hl7V2Messages.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.hl7V2Messages.ingest" class="permission-name add-link" data-text="healthcare.hl7V2Messages.ingest" tabindex="-1"><code dir="ltr" translate="no">healthcare.  hl7V2Messages.  ingest</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Ingest">Healthcare HL7v2 Message Ingest</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Ingest</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.hl7V2Messages.list" class="permission-name add-link" data-text="healthcare.hl7V2Messages.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.hl7V2Messages.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.hl7V2Messages.update" class="permission-name add-link" data-text="healthcare.hl7V2Messages.update" tabindex="-1"><code dir="ltr" translate="no">healthcare.  hl7V2Messages.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.hl7V2Stores.create" class="permission-name add-link" data-text="healthcare.hl7V2Stores.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.hl7V2Stores.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.hl7V2Stores.delete" class="permission-name add-link" data-text="healthcare.hl7V2Stores.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.hl7V2Stores.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.hl7V2Stores.export" class="permission-name add-link" data-text="healthcare.hl7V2Stores.export" tabindex="-1"><code dir="ltr" translate="no">healthcare.hl7V2Stores.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.hl7V2Stores.get" class="permission-name add-link" data-text="healthcare.hl7V2Stores.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.hl7V2Stores.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Ingest">Healthcare HL7v2 Message Ingest</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Ingest</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreViewer">Healthcare HL7v2 Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.hl7V2Stores.getIamPolicy" class="permission-name add-link" data-text="healthcare.hl7V2Stores.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">healthcare.  hl7V2Stores.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.hl7V2Stores.import" class="permission-name add-link" data-text="healthcare.hl7V2Stores.import" tabindex="-1"><code dir="ltr" translate="no">healthcare.hl7V2Stores.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.hl7V2Stores.list" class="permission-name add-link" data-text="healthcare.hl7V2Stores.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.hl7V2Stores.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Ingest">Healthcare HL7v2 Message Ingest</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Ingest</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreViewer">Healthcare HL7v2 Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.hl7V2Stores.rollback" class="permission-name add-link" data-text="healthcare.hl7V2Stores.rollback" tabindex="-1"><code dir="ltr" translate="no">healthcare.  hl7V2Stores.  rollback</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.hl7V2Stores.setIamPolicy" class="permission-name add-link" data-text="healthcare.hl7V2Stores.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">healthcare.  hl7V2Stores.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.hl7V2Stores.update" class="permission-name add-link" data-text="healthcare.hl7V2Stores.update" tabindex="-1"><code dir="ltr" translate="no">healthcare.hl7V2Stores.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.locations.get" class="permission-name add-link" data-text="healthcare.locations.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreViewer">Healthcare Annotation Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetViewer">Healthcare Dataset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreViewer">Healthcare DICOM Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreViewer">Healthcare FHIR Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Ingest">Healthcare HL7v2 Message Ingest</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Ingest</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreViewer">Healthcare HL7v2 Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.nlpServiceViewer">Healthcare NLP Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.nlpServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.locations.list" class="permission-name add-link" data-text="healthcare.locations.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreViewer">Healthcare Annotation Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetViewer">Healthcare Dataset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreViewer">Healthcare DICOM Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreViewer">Healthcare FHIR Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Ingest">Healthcare HL7v2 Message Ingest</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Ingest</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreViewer">Healthcare HL7v2 Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.nlpServiceViewer">Healthcare NLP Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.nlpServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.nlpservice.analyzeEntities" class="permission-name add-link" data-text="healthcare.nlpservice.analyzeEntities" tabindex="-1"><code dir="ltr" translate="no">healthcare.  nlpservice.  analyzeEntities</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.nlpServiceViewer">Healthcare NLP Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.nlpServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.operations.cancel" class="permission-name add-link" data-text="healthcare.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">healthcare.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.operations.get" class="permission-name add-link" data-text="healthcare.operations.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreViewer">Healthcare Annotation Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetViewer">Healthcare Dataset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreViewer">Healthcare DICOM Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreViewer">Healthcare FHIR Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Ingest">Healthcare HL7v2 Message Ingest</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Ingest</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreViewer">Healthcare HL7v2 Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.operations.list" class="permission-name add-link" data-text="healthcare.operations.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.userDataMappings.archive" class="permission-name add-link" data-text="healthcare.userDataMappings.archive" tabindex="-1"><code dir="ltr" translate="no">healthcare.  userDataMappings.  archive</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.userDataMappings.create" class="permission-name add-link" data-text="healthcare.userDataMappings.create" tabindex="-1"><code dir="ltr" translate="no">healthcare.  userDataMappings.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.userDataMappings.delete" class="permission-name add-link" data-text="healthcare.userDataMappings.delete" tabindex="-1"><code dir="ltr" translate="no">healthcare.  userDataMappings.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.userDataMappings.get" class="permission-name add-link" data-text="healthcare.userDataMappings.get" tabindex="-1"><code dir="ltr" translate="no">healthcare.  userDataMappings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="healthcare.userDataMappings.list" class="permission-name add-link" data-text="healthcare.userDataMappings.list" tabindex="-1"><code dir="ltr" translate="no">healthcare.  userDataMappings.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="healthcare.userDataMappings.update" class="permission-name add-link" data-text="healthcare.userDataMappings.update" tabindex="-1"><code dir="ltr" translate="no">healthcare.  userDataMappings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p></td>
</tr>
</tbody>
</table>
