---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/composer
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/composer
title: Managed Service for Apache Airflow roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Managed Service for Apache Airflow. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Managed Service for Apache Airflow roles

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
<td><h4 id="composer.admin" class="role-title add-link" data-text="Composer Administrator" tabindex="-1">Composer Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p>Provides full control of Managed Airflow resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">composer.*</code></p>
<ul>
<li><code dir="ltr" translate="no">composer.dags.execute</code></li>
<li><code dir="ltr" translate="no">composer.dags.get</code></li>
<li><code dir="ltr" translate="no">composer.dags.getSourceCode</code></li>
<li><code dir="ltr" translate="no">composer.dags.list</code></li>
<li><code dir="ltr" translate="no">composer.environments.create</code></li>
<li><code dir="ltr" translate="no">composer.  environments.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">composer.environments.delete</code></li>
<li><code dir="ltr" translate="no">composer.  environments.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">composer.  environments.  executeAirflowCommand</code></li>
<li><code dir="ltr" translate="no">composer.environments.get</code></li>
<li><code dir="ltr" translate="no">composer.environments.list</code></li>
<li><code dir="ltr" translate="no">composer.  environments.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">composer.  environments.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">composer.environments.update</code></li>
<li><code dir="ltr" translate="no">composer.imageversions.list</code></li>
<li><code dir="ltr" translate="no">composer.operations.delete</code></li>
<li><code dir="ltr" translate="no">composer.operations.get</code></li>
<li><code dir="ltr" translate="no">composer.operations.list</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  create</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  delete</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  get</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  list</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  update</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  create</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  delete</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  get</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  list</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="composer.editor" class="role-title add-link" data-text="Composer Editor" tabindex="-1">Composer Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p>Editor role for Composer</p></td>
<td><p><code dir="ltr" translate="no">composer.dags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">composer.dags.execute</code></li>
<li><code dir="ltr" translate="no">composer.dags.get</code></li>
<li><code dir="ltr" translate="no">composer.dags.getSourceCode</code></li>
<li><code dir="ltr" translate="no">composer.dags.list</code></li>
</ul>
<p><code dir="ltr" translate="no">composer.environments.create</code></p>
<p><code dir="ltr" translate="no">composer.environments.delete</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  executeAirflowCommand</code></p>
<p><code dir="ltr" translate="no">composer.environments.get</code></p>
<p><code dir="ltr" translate="no">composer.environments.list</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">composer.environments.update</code></p>
<p><code dir="ltr" translate="no">composer.imageversions.list</code></p>
<p><code dir="ltr" translate="no">composer.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">composer.operations.delete</code></li>
<li><code dir="ltr" translate="no">composer.operations.get</code></li>
<li><code dir="ltr" translate="no">composer.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  create</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  delete</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  get</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  list</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">composer.  userworkloadssecrets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  create</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  delete</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  get</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  list</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.user" class="role-title add-link" data-text="Composer User" tabindex="-1">Composer User</h4>
<p>( <code dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p>Provides the permissions necessary to list and get Managed Airflow environments and operations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">composer.dags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">composer.dags.execute</code></li>
<li><code dir="ltr" translate="no">composer.dags.get</code></li>
<li><code dir="ltr" translate="no">composer.dags.getSourceCode</code></li>
<li><code dir="ltr" translate="no">composer.dags.list</code></li>
</ul>
<p><code dir="ltr" translate="no">composer.environments.get</code></p>
<p><code dir="ltr" translate="no">composer.environments.list</code></p>
<p><code dir="ltr" translate="no">composer.imageversions.list</code></p>
<p><code dir="ltr" translate="no">composer.operations.get</code></p>
<p><code dir="ltr" translate="no">composer.operations.list</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  get</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  list</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadssecrets.  get</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadssecrets.  list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="composer.viewer" class="role-title add-link" data-text="Composer Viewer" tabindex="-1">Composer Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p>Viewer role for Composer</p></td>
<td><p><code dir="ltr" translate="no">composer.dags.get</code></p>
<p><code dir="ltr" translate="no">composer.dags.getSourceCode</code></p>
<p><code dir="ltr" translate="no">composer.dags.list</code></p>
<p><code dir="ltr" translate="no">composer.environments.get</code></p>
<p><code dir="ltr" translate="no">composer.environments.list</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">composer.imageversions.list</code></p>
<p><code dir="ltr" translate="no">composer.operations.get</code></p>
<p><code dir="ltr" translate="no">composer.operations.list</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  get</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  list</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadssecrets.  get</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadssecrets.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.ServiceAgentV2Ext" class="role-title add-link" data-text="Cloud Composer v2 API Service Agent Extension" tabindex="-1">Cloud Composer v2 API Service Agent Extension</h4>
<p>( <code dir="ltr" translate="no">roles/  composer.ServiceAgentV2Ext</code> )</p>
<p>Cloud Composer v2 API Service Agent Extension is a supplementary role required to manage Composer v2 environments.</p></td>
<td><p><code dir="ltr" translate="no">iam.  serviceAccounts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  setIamPolicy</code></p></td>
</tr>
<tr class="even">
<td><h4 id="composer.environmentAndStorageObjectAdmin" class="role-title add-link" data-text="Environment and Storage Object Administrator" tabindex="-1">Environment and Storage Object Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p>Provides full control of Managed Airflow resources and of the objects in all project buckets.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">composer.*</code></p>
<ul>
<li><code dir="ltr" translate="no">composer.dags.execute</code></li>
<li><code dir="ltr" translate="no">composer.dags.get</code></li>
<li><code dir="ltr" translate="no">composer.dags.getSourceCode</code></li>
<li><code dir="ltr" translate="no">composer.dags.list</code></li>
<li><code dir="ltr" translate="no">composer.environments.create</code></li>
<li><code dir="ltr" translate="no">composer.  environments.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">composer.environments.delete</code></li>
<li><code dir="ltr" translate="no">composer.  environments.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">composer.  environments.  executeAirflowCommand</code></li>
<li><code dir="ltr" translate="no">composer.environments.get</code></li>
<li><code dir="ltr" translate="no">composer.environments.list</code></li>
<li><code dir="ltr" translate="no">composer.  environments.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">composer.  environments.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">composer.environments.update</code></li>
<li><code dir="ltr" translate="no">composer.imageversions.list</code></li>
<li><code dir="ltr" translate="no">composer.operations.delete</code></li>
<li><code dir="ltr" translate="no">composer.operations.get</code></li>
<li><code dir="ltr" translate="no">composer.operations.list</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  create</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  delete</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  get</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  list</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  update</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  create</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  delete</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  get</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  list</code></li>
<li><code dir="ltr" translate="no">composer.  userworkloadssecrets.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.folders.create</code></li>
<li><code dir="ltr" translate="no">storage.folders.delete</code></li>
<li><code dir="ltr" translate="no">storage.folders.get</code></li>
<li><code dir="ltr" translate="no">storage.folders.list</code></li>
<li><code dir="ltr" translate="no">storage.folders.rename</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.managedFolders.create</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.delete</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
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
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="composer.environmentAndStorageObjectUser" class="role-title add-link" data-text="Environment and Storage Object User" tabindex="-1">Environment and Storage Object User</h4>
<p>( <code dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p>Read and use access to Cloud Composer resources and read access to Cloud Storage objects.</p></td>
<td><p><code dir="ltr" translate="no">composer.dags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">composer.dags.execute</code></li>
<li><code dir="ltr" translate="no">composer.dags.get</code></li>
<li><code dir="ltr" translate="no">composer.dags.getSourceCode</code></li>
<li><code dir="ltr" translate="no">composer.dags.list</code></li>
</ul>
<p><code dir="ltr" translate="no">composer.environments.get</code></p>
<p><code dir="ltr" translate="no">composer.environments.list</code></p>
<p><code dir="ltr" translate="no">composer.imageversions.list</code></p>
<p><code dir="ltr" translate="no">composer.operations.get</code></p>
<p><code dir="ltr" translate="no">composer.operations.list</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  get</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  list</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadssecrets.  get</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadssecrets.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.folders.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="composer.environmentAndStorageObjectViewer" class="role-title add-link" data-text="Environment and Storage Object Viewer" tabindex="-1">Environment and Storage Object Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p>Provides the permissions necessary to list and get Managed Airflow environments and operations. Provides read-only access to objects in all project buckets.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">composer.dags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">composer.dags.execute</code></li>
<li><code dir="ltr" translate="no">composer.dags.get</code></li>
<li><code dir="ltr" translate="no">composer.dags.getSourceCode</code></li>
<li><code dir="ltr" translate="no">composer.dags.list</code></li>
</ul>
<p><code dir="ltr" translate="no">composer.environments.get</code></p>
<p><code dir="ltr" translate="no">composer.environments.list</code></p>
<p><code dir="ltr" translate="no">composer.imageversions.list</code></p>
<p><code dir="ltr" translate="no">composer.operations.get</code></p>
<p><code dir="ltr" translate="no">composer.operations.list</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  get</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  list</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadssecrets.  get</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadssecrets.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.folders.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.sharedVpcAgent" class="role-title add-link" data-text="Composer Shared VPC Agent" tabindex="-1">Composer Shared VPC Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  composer.sharedVpcAgent</code> )</p>
<p>Role that should be assigned to Composer Agent service account in Shared VPC host project</p></td>
<td><p><code dir="ltr" translate="no">compute.  networkAttachments.  create</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  delete</code></p>
<p><code dir="ltr" translate="no">compute.networkAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  update</code></p>
<p><code dir="ltr" translate="no">compute.networks.access</code></p>
<p><code dir="ltr" translate="no">compute.networks.addPeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.networks.useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.managedZones.get</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></p></td>
</tr>
<tr class="even">
<td><h4 id="composer.worker" class="role-title add-link" data-text="Composer Worker" tabindex="-1">Composer Worker</h4>
<p>( <code dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Provides the permissions necessary to run a Managed Airflow environment VM. Intended for service accounts.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">artifactregistry.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  aptartifacts.  create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  files.  download</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.upload</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  kfpartifacts.  create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  locations.  list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  packages.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.packages.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.packages.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  packages.  update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  projectsettings.  update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  createOnPush</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteArtifacts</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  versions.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.versions.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.versions.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  versions.  update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  yumartifacts.  create</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.builds.create</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.update</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.workerpools.use</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">composer.environments.get</code></p>
<p><code dir="ltr" translate="no">compute.images.create</code></p>
<p><code dir="ltr" translate="no">container.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.apiServices.create</code></li>
<li><code dir="ltr" translate="no">container.apiServices.delete</code></li>
<li><code dir="ltr" translate="no">container.apiServices.get</code></li>
<li><code dir="ltr" translate="no">container.  apiServices.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.apiServices.list</code></li>
<li><code dir="ltr" translate="no">container.apiServices.update</code></li>
<li><code dir="ltr" translate="no">container.  apiServices.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.create</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.delete</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.get</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.list</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.update</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  update</code></li>
<li><code dir="ltr" translate="no">container.bindings.create</code></li>
<li><code dir="ltr" translate="no">container.bindings.delete</code></li>
<li><code dir="ltr" translate="no">container.bindings.get</code></li>
<li><code dir="ltr" translate="no">container.bindings.list</code></li>
<li><code dir="ltr" translate="no">container.bindings.update</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  approve</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  create</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  delete</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  get</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  list</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  update</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  create</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  get</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  list</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  update</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.bind</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.create</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoles.  escalate</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.get</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.list</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.update</code></li>
<li><code dir="ltr" translate="no">container.clusters.connect</code></li>
<li><code dir="ltr" translate="no">container.clusters.create</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">container.clusters.delete</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">container.clusters.get</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  getCredentials</code></li>
<li><code dir="ltr" translate="no">container.clusters.impersonate</code></li>
<li><code dir="ltr" translate="no">container.clusters.list</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">container.clusters.update</code></li>
<li><code dir="ltr" translate="no">container.  componentStatuses.  get</code></li>
<li><code dir="ltr" translate="no">container.  componentStatuses.  list</code></li>
<li><code dir="ltr" translate="no">container.configMaps.create</code></li>
<li><code dir="ltr" translate="no">container.configMaps.delete</code></li>
<li><code dir="ltr" translate="no">container.configMaps.get</code></li>
<li><code dir="ltr" translate="no">container.configMaps.list</code></li>
<li><code dir="ltr" translate="no">container.configMaps.update</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  create</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  get</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  list</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  update</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.create</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.delete</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.get</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.getStatus</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.list</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.update</code></li>
<li><code dir="ltr" translate="no">container.  cronJobs.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.create</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.delete</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.get</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.list</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.update</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.create</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.delete</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.get</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.list</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.update</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.create</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.delete</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.get</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.list</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.update</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  create</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  delete</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  get</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  update</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.create</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.delete</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.get</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.getStatus</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.list</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.update</code></li>
<li><code dir="ltr" translate="no">container.  daemonSets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.deployments.create</code></li>
<li><code dir="ltr" translate="no">container.deployments.delete</code></li>
<li><code dir="ltr" translate="no">container.deployments.get</code></li>
<li><code dir="ltr" translate="no">container.deployments.getScale</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.deployments.list</code></li>
<li><code dir="ltr" translate="no">container.deployments.rollback</code></li>
<li><code dir="ltr" translate="no">container.deployments.update</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  create</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  delete</code></li>
<li><code dir="ltr" translate="no">container.endpointSlices.get</code></li>
<li><code dir="ltr" translate="no">container.endpointSlices.list</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  update</code></li>
<li><code dir="ltr" translate="no">container.endpoints.create</code></li>
<li><code dir="ltr" translate="no">container.endpoints.delete</code></li>
<li><code dir="ltr" translate="no">container.endpoints.get</code></li>
<li><code dir="ltr" translate="no">container.endpoints.list</code></li>
<li><code dir="ltr" translate="no">container.endpoints.update</code></li>
<li><code dir="ltr" translate="no">container.events.create</code></li>
<li><code dir="ltr" translate="no">container.events.delete</code></li>
<li><code dir="ltr" translate="no">container.events.get</code></li>
<li><code dir="ltr" translate="no">container.events.list</code></li>
<li><code dir="ltr" translate="no">container.events.update</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.frontendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.frontendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  update</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  create</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  delete</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  get</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  list</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  update</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.hostServiceAgent.use</code></li>
<li><code dir="ltr" translate="no">container.ingresses.create</code></li>
<li><code dir="ltr" translate="no">container.ingresses.delete</code></li>
<li><code dir="ltr" translate="no">container.ingresses.get</code></li>
<li><code dir="ltr" translate="no">container.ingresses.getStatus</code></li>
<li><code dir="ltr" translate="no">container.ingresses.list</code></li>
<li><code dir="ltr" translate="no">container.ingresses.update</code></li>
<li><code dir="ltr" translate="no">container.  ingresses.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  update</code></li>
<li><code dir="ltr" translate="no">container.jobs.create</code></li>
<li><code dir="ltr" translate="no">container.jobs.delete</code></li>
<li><code dir="ltr" translate="no">container.jobs.get</code></li>
<li><code dir="ltr" translate="no">container.jobs.getStatus</code></li>
<li><code dir="ltr" translate="no">container.jobs.list</code></li>
<li><code dir="ltr" translate="no">container.jobs.update</code></li>
<li><code dir="ltr" translate="no">container.jobs.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.leases.create</code></li>
<li><code dir="ltr" translate="no">container.leases.delete</code></li>
<li><code dir="ltr" translate="no">container.leases.get</code></li>
<li><code dir="ltr" translate="no">container.leases.list</code></li>
<li><code dir="ltr" translate="no">container.leases.update</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.create</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.delete</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.get</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.list</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.update</code></li>
<li><code dir="ltr" translate="no">container.  localSubjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  localSubjectAccessReviews.  list</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  create</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  delete</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  get</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  list</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  update</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  update</code></li>
<li><code dir="ltr" translate="no">container.namespaces.create</code></li>
<li><code dir="ltr" translate="no">container.namespaces.delete</code></li>
<li><code dir="ltr" translate="no">container.namespaces.finalize</code></li>
<li><code dir="ltr" translate="no">container.namespaces.get</code></li>
<li><code dir="ltr" translate="no">container.namespaces.getStatus</code></li>
<li><code dir="ltr" translate="no">container.namespaces.list</code></li>
<li><code dir="ltr" translate="no">container.namespaces.update</code></li>
<li><code dir="ltr" translate="no">container.  namespaces.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  create</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">container.networkPolicies.get</code></li>
<li><code dir="ltr" translate="no">container.networkPolicies.list</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  update</code></li>
<li><code dir="ltr" translate="no">container.nodes.create</code></li>
<li><code dir="ltr" translate="no">container.nodes.delete</code></li>
<li><code dir="ltr" translate="no">container.nodes.get</code></li>
<li><code dir="ltr" translate="no">container.nodes.getStatus</code></li>
<li><code dir="ltr" translate="no">container.nodes.list</code></li>
<li><code dir="ltr" translate="no">container.nodes.proxy</code></li>
<li><code dir="ltr" translate="no">container.nodes.update</code></li>
<li><code dir="ltr" translate="no">container.nodes.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.operations.get</code></li>
<li><code dir="ltr" translate="no">container.operations.list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  create</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  delete</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  get</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  update</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  create</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  delete</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  get</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  update</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.petSets.create</code></li>
<li><code dir="ltr" translate="no">container.petSets.delete</code></li>
<li><code dir="ltr" translate="no">container.petSets.get</code></li>
<li><code dir="ltr" translate="no">container.petSets.list</code></li>
<li><code dir="ltr" translate="no">container.petSets.update</code></li>
<li><code dir="ltr" translate="no">container.petSets.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  create</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  delete</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  get</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  list</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  update</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.podPresets.create</code></li>
<li><code dir="ltr" translate="no">container.podPresets.delete</code></li>
<li><code dir="ltr" translate="no">container.podPresets.get</code></li>
<li><code dir="ltr" translate="no">container.podPresets.list</code></li>
<li><code dir="ltr" translate="no">container.podPresets.update</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  create</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  get</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  list</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  update</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  use</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.create</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.delete</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.get</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.list</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.update</code></li>
<li><code dir="ltr" translate="no">container.pods.attach</code></li>
<li><code dir="ltr" translate="no">container.pods.create</code></li>
<li><code dir="ltr" translate="no">container.pods.delete</code></li>
<li><code dir="ltr" translate="no">container.pods.evict</code></li>
<li><code dir="ltr" translate="no">container.pods.exec</code></li>
<li><code dir="ltr" translate="no">container.pods.get</code></li>
<li><code dir="ltr" translate="no">container.pods.getLogs</code></li>
<li><code dir="ltr" translate="no">container.pods.getStatus</code></li>
<li><code dir="ltr" translate="no">container.pods.initialize</code></li>
<li><code dir="ltr" translate="no">container.pods.list</code></li>
<li><code dir="ltr" translate="no">container.pods.portForward</code></li>
<li><code dir="ltr" translate="no">container.pods.proxy</code></li>
<li><code dir="ltr" translate="no">container.pods.update</code></li>
<li><code dir="ltr" translate="no">container.pods.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.priorityClasses.get</code></li>
<li><code dir="ltr" translate="no">container.priorityClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.create</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.delete</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.get</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.getScale</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.list</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.update</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  create</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  delete</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  get</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  getScale</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  list</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  update</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  create</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  delete</code></li>
<li><code dir="ltr" translate="no">container.resourceQuotas.get</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.resourceQuotas.list</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  update</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.create</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.delete</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.get</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.list</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.update</code></li>
<li><code dir="ltr" translate="no">container.roles.bind</code></li>
<li><code dir="ltr" translate="no">container.roles.create</code></li>
<li><code dir="ltr" translate="no">container.roles.delete</code></li>
<li><code dir="ltr" translate="no">container.roles.escalate</code></li>
<li><code dir="ltr" translate="no">container.roles.get</code></li>
<li><code dir="ltr" translate="no">container.roles.list</code></li>
<li><code dir="ltr" translate="no">container.roles.update</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.runtimeClasses.get</code></li>
<li><code dir="ltr" translate="no">container.runtimeClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.create</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.delete</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.get</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.list</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.update</code></li>
<li><code dir="ltr" translate="no">container.  scheduledJobs.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.secrets.create</code></li>
<li><code dir="ltr" translate="no">container.secrets.delete</code></li>
<li><code dir="ltr" translate="no">container.secrets.get</code></li>
<li><code dir="ltr" translate="no">container.secrets.list</code></li>
<li><code dir="ltr" translate="no">container.secrets.update</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.  list</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectRulesReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  create</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  createToken</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  delete</code></li>
<li><code dir="ltr" translate="no">container.serviceAccounts.get</code></li>
<li><code dir="ltr" translate="no">container.serviceAccounts.list</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  update</code></li>
<li><code dir="ltr" translate="no">container.services.create</code></li>
<li><code dir="ltr" translate="no">container.services.delete</code></li>
<li><code dir="ltr" translate="no">container.services.get</code></li>
<li><code dir="ltr" translate="no">container.services.getStatus</code></li>
<li><code dir="ltr" translate="no">container.services.list</code></li>
<li><code dir="ltr" translate="no">container.services.proxy</code></li>
<li><code dir="ltr" translate="no">container.services.update</code></li>
<li><code dir="ltr" translate="no">container.  services.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.create</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.delete</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.get</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  getScale</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.list</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.update</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.storageClasses.get</code></li>
<li><code dir="ltr" translate="no">container.storageClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.storageStates.create</code></li>
<li><code dir="ltr" translate="no">container.storageStates.delete</code></li>
<li><code dir="ltr" translate="no">container.storageStates.get</code></li>
<li><code dir="ltr" translate="no">container.  storageStates.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.storageStates.list</code></li>
<li><code dir="ltr" translate="no">container.storageStates.update</code></li>
<li><code dir="ltr" translate="no">container.  storageStates.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  create</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  get</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  list</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  update</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  subjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  subjectAccessReviews.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  update</code></li>
<li><code dir="ltr" translate="no">container.tokenReviews.create</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.create</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.delete</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.get</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.list</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.update</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  delete</code></li>
<li><code dir="ltr" translate="no">container.volumeSnapshots.get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.volumeSnapshots.list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  create</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  delete</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  update</code></p>
<p><code dir="ltr" translate="no">datalineage.events.create</code></p>
<p><code dir="ltr" translate="no">datalineage.  locations.  processOpenLineageMessage</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.create</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.get</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.update</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.create</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.get</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.update</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">logging.views.access</code></p>
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
<p><code dir="ltr" translate="no">pubsub.  messageTransforms.  validate</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.attach</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.commit</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.create</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.get</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.list</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.listRevisions</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.rollback</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.validate</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.create</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.get</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.seek</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.update</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.update</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  detachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.update</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.updateTag</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">source.repos.get</code></p>
<p><code dir="ltr" translate="no">source.repos.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.folders.create</code></li>
<li><code dir="ltr" translate="no">storage.folders.delete</code></li>
<li><code dir="ltr" translate="no">storage.folders.get</code></li>
<li><code dir="ltr" translate="no">storage.folders.list</code></li>
<li><code dir="ltr" translate="no">storage.folders.rename</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.managedFolders.create</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.delete</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
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
</ul></td>
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
<td><h4 id="composer.serviceAgent" class="role-title add-link" data-text="Cloud Composer API Service Agent" tabindex="-1">Cloud Composer API Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</p>
<p>Cloud Composer API service agent can manage environments.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">appengine.  applications.  listRuntimes</code></p>
<p><code dir="ltr" translate="no">appengine.applications.update</code></p>
<p><code dir="ltr" translate="no">appengine.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.instances.delete</code></li>
<li><code dir="ltr" translate="no">appengine.  instances.  enableDebug</code></li>
<li><code dir="ltr" translate="no">appengine.instances.get</code></li>
<li><code dir="ltr" translate="no">appengine.instances.list</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.memcache.addKey</code></p>
<p><code dir="ltr" translate="no">appengine.memcache.flush</code></p>
<p><code dir="ltr" translate="no">appengine.memcache.get</code></p>
<p><code dir="ltr" translate="no">appengine.memcache.update</code></p>
<p><code dir="ltr" translate="no">appengine.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.operations.get</code></li>
<li><code dir="ltr" translate="no">appengine.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.runtimes.actAsAdmin</code></p>
<p><code dir="ltr" translate="no">appengine.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.services.delete</code></li>
<li><code dir="ltr" translate="no">appengine.services.get</code></li>
<li><code dir="ltr" translate="no">appengine.services.list</code></li>
<li><code dir="ltr" translate="no">appengine.services.update</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.versions.create</code></p>
<p><code dir="ltr" translate="no">appengine.versions.delete</code></p>
<p><code dir="ltr" translate="no">appengine.  versions.  exportAppImage</code></p>
<p><code dir="ltr" translate="no">appengine.versions.get</code></p>
<p><code dir="ltr" translate="no">appengine.versions.list</code></p>
<p><code dir="ltr" translate="no">appengine.versions.update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  delete</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.companions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudaicompanion.  companions.  generateChat</code></li>
<li><code dir="ltr" translate="no">cloudaicompanion.  companions.  generateCode</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudaicompanion.  entitlements.  get</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  completeCode</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  completeTask</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  generateCode</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">cloudsql.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsql.backupRuns.create</code></li>
<li><code dir="ltr" translate="no">cloudsql.backupRuns.delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.backupRuns.export</code></li>
<li><code dir="ltr" translate="no">cloudsql.backupRuns.get</code></li>
<li><code dir="ltr" translate="no">cloudsql.backupRuns.list</code></li>
<li><code dir="ltr" translate="no">cloudsql.backupRuns.update</code></li>
<li><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  create</code></li>
<li><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  get</code></li>
<li><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  list</code></li>
<li><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  switchover</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.create</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.get</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.list</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.update</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  addEntraIdCertificate</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.addServerCa</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  addServerCertificate</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.clone</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.connect</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.create</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  createBackupDrBackup</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  demoteMaster</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.executeSql</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.export</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.failover</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.get</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  getDiskShrinkConfig</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.import</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.list</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  listEntraIdCertificates</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  listServerCas</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  listServerCertificates</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.login</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  manageEncryption</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.migrate</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  performDiskShrink</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  preCheckMajorVersionUpgrade</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  promoteReplica</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.reencrypt</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  resetReplicaSize</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  resetSslConfig</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.restart</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  restoreBackup</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  rotateEntraIdCertificate</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  rotateServerCa</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  rotateServerCertificate</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  startReplica</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.stopReplica</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.truncateLog</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.update</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  updateBackupDrConfig</code></li>
<li><code dir="ltr" translate="no">cloudsql.schemas.view</code></li>
<li><code dir="ltr" translate="no">cloudsql.sslCerts.create</code></li>
<li><code dir="ltr" translate="no">cloudsql.sslCerts.delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.sslCerts.get</code></li>
<li><code dir="ltr" translate="no">cloudsql.sslCerts.list</code></li>
<li><code dir="ltr" translate="no">cloudsql.users.create</code></li>
<li><code dir="ltr" translate="no">cloudsql.users.delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.users.get</code></li>
<li><code dir="ltr" translate="no">cloudsql.users.list</code></li>
<li><code dir="ltr" translate="no">cloudsql.users.update</code></li>
</ul>
<p><code dir="ltr" translate="no">composer.dags.get</code></p>
<p><code dir="ltr" translate="no">composer.environments.get</code></p>
<p><code dir="ltr" translate="no">compute.acceleratorTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.addresses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.addresses.create</code></li>
<li><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></li>
<li><code dir="ltr" translate="no">compute.  addresses.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.addresses.delete</code></li>
<li><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></li>
<li><code dir="ltr" translate="no">compute.  addresses.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.addresses.get</code></li>
<li><code dir="ltr" translate="no">compute.addresses.list</code></li>
<li><code dir="ltr" translate="no">compute.  addresses.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  addresses.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.addresses.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.addresses.use</code></li>
<li><code dir="ltr" translate="no">compute.addresses.useInternal</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.autoscalers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.autoscalers.create</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.delete</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.get</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.list</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.backendBuckets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  addSignedUrlKey</code></li>
<li><code dir="ltr" translate="no">compute.backendBuckets.create</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.backendBuckets.delete</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  deleteSignedUrlKey</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.backendBuckets.get</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.backendBuckets.list</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.backendBuckets.update</code></li>
<li><code dir="ltr" translate="no">compute.backendBuckets.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.backendServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  backendServices.  addSignedUrlKey</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.create</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.delete</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  deleteSignedUrlKey</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.get</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.list</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.update</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  crossSiteNetworks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  crossSiteNetworks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.crossSiteNetworks.get</code></li>
<li><code dir="ltr" translate="no">compute.crossSiteNetworks.list</code></li>
<li><code dir="ltr" translate="no">compute.  crossSiteNetworks.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.diskSettings.get</code></p>
<p><code dir="ltr" translate="no">compute.diskTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.diskTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.diskTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.disks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  disks.  addResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.disks.create</code></li>
<li><code dir="ltr" translate="no">compute.disks.createSnapshot</code></li>
<li><code dir="ltr" translate="no">compute.disks.createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.disks.delete</code></li>
<li><code dir="ltr" translate="no">compute.disks.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.disks.get</code></li>
<li><code dir="ltr" translate="no">compute.disks.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.disks.list</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.disks.listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  removeResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.disks.resize</code></li>
<li><code dir="ltr" translate="no">compute.disks.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.disks.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  startAsyncReplication</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  stopAsyncReplication</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  stopGroupAsyncReplication</code></li>
<li><code dir="ltr" translate="no">compute.disks.update</code></li>
<li><code dir="ltr" translate="no">compute.disks.updateKmsKey</code></li>
<li><code dir="ltr" translate="no">compute.disks.use</code></li>
<li><code dir="ltr" translate="no">compute.disks.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.externalVpnGateways.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  create</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  get</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  list</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.firewallPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.forwardingRules.create</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.delete</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.get</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.list</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  pscCreate</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  pscDelete</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  pscSetLabels</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  pscUpdate</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  setTarget</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.update</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.globalAddresses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.globalAddresses.create</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  createInternal</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.globalAddresses.delete</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  deleteInternal</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.globalAddresses.get</code></li>
<li><code dir="ltr" translate="no">compute.globalAddresses.list</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.globalAddresses.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  create</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscCreate</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscDelete</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscSetLabels</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscUpdate</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  setTarget</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  attachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  detachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalPublicDelegatedPrefixes.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  globalPublicDelegatedPrefixes.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalPublicDelegatedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalPublicDelegatedPrefixes.  updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.healthChecks.create</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.delete</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.get</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.list</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.update</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.use</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.hosts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.hosts.get</code></li>
<li><code dir="ltr" translate="no">compute.hosts.getVersion</code></li>
<li><code dir="ltr" translate="no">compute.hosts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></li>
<li><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  update</code></li>
<li><code dir="ltr" translate="no">compute.httpHealthChecks.use</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.httpsHealthChecks.get</code></li>
<li><code dir="ltr" translate="no">compute.httpsHealthChecks.list</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  update</code></li>
<li><code dir="ltr" translate="no">compute.httpsHealthChecks.use</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.images.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.images.create</code></li>
<li><code dir="ltr" translate="no">compute.  images.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.images.delete</code></li>
<li><code dir="ltr" translate="no">compute.  images.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.images.deprecate</code></li>
<li><code dir="ltr" translate="no">compute.images.get</code></li>
<li><code dir="ltr" translate="no">compute.images.getFromFamily</code></li>
<li><code dir="ltr" translate="no">compute.images.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.images.list</code></li>
<li><code dir="ltr" translate="no">compute.  images.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.images.listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.images.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.images.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.images.update</code></li>
<li><code dir="ltr" translate="no">compute.images.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  create</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  get</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  list</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  update</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instanceGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.instanceGroups.create</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.delete</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.get</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.list</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.update</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instanceSettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.instanceSettings.get</code></li>
<li><code dir="ltr" translate="no">compute.  instanceSettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instanceTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  create</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">compute.instanceTemplates.get</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.instanceTemplates.list</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instances.  addAccessConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  addNetworkInterface</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  addResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.instances.attachDisk</code></li>
<li><code dir="ltr" translate="no">compute.instances.create</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instances.delete</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  deleteAccessConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  deleteNetworkInterface</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instances.detachDisk</code></li>
<li><code dir="ltr" translate="no">compute.instances.get</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getEffectiveFirewalls</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getGuestAttributes</code></li>
<li><code dir="ltr" translate="no">compute.instances.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getScreenshot</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getSerialPortOutput</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getShieldedInstanceIdentity</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getShieldedVmIdentity</code></li>
<li><code dir="ltr" translate="no">compute.instances.list</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  listReferrers</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.instances.osAdminLogin</code></li>
<li><code dir="ltr" translate="no">compute.instances.osLogin</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  pscInterfaceCreate</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  removeResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.instances.reset</code></li>
<li><code dir="ltr" translate="no">compute.instances.resume</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  sendDiagnosticInterrupt</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setDeletionProtection</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setDiskAutoDelete</code></li>
<li><code dir="ltr" translate="no">compute.instances.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.instances.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setMachineResources</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setMachineType</code></li>
<li><code dir="ltr" translate="no">compute.instances.setMetadata</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setMinCpuPlatform</code></li>
<li><code dir="ltr" translate="no">compute.instances.setName</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setScheduling</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setServiceAccount</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setShieldedInstanceIntegrityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setShieldedVmIntegrityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.instances.setTags</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  simulateMaintenanceEvent</code></li>
<li><code dir="ltr" translate="no">compute.instances.start</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  startWithEncryptionKey</code></li>
<li><code dir="ltr" translate="no">compute.instances.stop</code></li>
<li><code dir="ltr" translate="no">compute.instances.suspend</code></li>
<li><code dir="ltr" translate="no">compute.instances.update</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateAccessConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateDisplayDevice</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateNetworkInterface</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateSecurity</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateShieldedInstanceConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateShieldedVmConfig</code></li>
<li><code dir="ltr" translate="no">compute.instances.use</code></li>
<li><code dir="ltr" translate="no">compute.instances.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  instantSnapshotGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  export</code></p>
<p><code dir="ltr" translate="no">compute.instantSnapshots.get</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instantSnapshots.list</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  patch</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  create</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  list</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  update</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.interconnectGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.interconnectGroups.get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectGroups.  patch</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  interconnectLocations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectLocations.  get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectLocations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.  get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.interconnects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.interconnects.create</code></li>
<li><code dir="ltr" translate="no">compute.  interconnects.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.interconnects.delete</code></li>
<li><code dir="ltr" translate="no">compute.  interconnects.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.interconnects.get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnects.  getMacsecConfig</code></li>
<li><code dir="ltr" translate="no">compute.interconnects.list</code></li>
<li><code dir="ltr" translate="no">compute.  interconnects.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  interconnects.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  interconnects.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.interconnects.update</code></li>
<li><code dir="ltr" translate="no">compute.interconnects.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.licenseCodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.licenseCodes.get</code></li>
<li><code dir="ltr" translate="no">compute.  licenseCodes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.licenseCodes.list</code></li>
<li><code dir="ltr" translate="no">compute.  licenseCodes.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.licenses.create</code></p>
<p><code dir="ltr" translate="no">compute.licenses.delete</code></p>
<p><code dir="ltr" translate="no">compute.licenses.get</code></p>
<p><code dir="ltr" translate="no">compute.licenses.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenses.list</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.licenses.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenses.update</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.create</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.delete</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.get</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.list</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.machineTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.machineTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.multiMig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.multiMig.create</code></li>
<li><code dir="ltr" translate="no">compute.multiMig.delete</code></li>
<li><code dir="ltr" translate="no">compute.multiMig.get</code></li>
<li><code dir="ltr" translate="no">compute.multiMig.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.multiMigMembers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.multiMigMembers.get</code></li>
<li><code dir="ltr" translate="no">compute.multiMigMembers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networkAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  create</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.networkAttachments.get</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  update</code></li>
<li><code dir="ltr" translate="no">compute.networkAttachments.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  attachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  detachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networkProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.networkProfiles.get</code></li>
<li><code dir="ltr" translate="no">compute.networkProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.networks.access</code></li>
<li><code dir="ltr" translate="no">compute.networks.addPeering</code></li>
<li><code dir="ltr" translate="no">compute.networks.create</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.networks.delete</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.networks.get</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  getEffectiveFirewalls</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  getRegionEffectiveFirewalls</code></li>
<li><code dir="ltr" translate="no">compute.networks.list</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.networks.mirror</code></li>
<li><code dir="ltr" translate="no">compute.networks.removePeering</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  setFirewallPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  setNetworkPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  switchToCustomMode</code></li>
<li><code dir="ltr" translate="no">compute.networks.update</code></li>
<li><code dir="ltr" translate="no">compute.networks.updatePeering</code></li>
<li><code dir="ltr" translate="no">compute.networks.updatePolicy</code></li>
<li><code dir="ltr" translate="no">compute.networks.use</code></li>
<li><code dir="ltr" translate="no">compute.networks.useExternalIp</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.packetMirrorings.get</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.list</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.  projects.  setCommonInstanceMetadata</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  get</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  update</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.regionBackendBuckets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  use</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regionHealthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.regionHealthChecks.get</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  update</code></li>
<li><code dir="ltr" translate="no">compute.regionHealthChecks.use</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regionHealthSources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionHealthSources.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthSources.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthSources.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthSources.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthSources.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  attachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  detachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  use</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.regionSslPolicies.get</code></li>
<li><code dir="ltr" translate="no">compute.regionSslPolicies.list</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  listAvailableFeatures</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  update</code></li>
<li><code dir="ltr" translate="no">compute.regionSslPolicies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  setUrlMap</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  setSslCertificates</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  setUrlMap</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  attach</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.create</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.get</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  invalidateCache</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.list</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.update</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.use</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.validate</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.reservationBlocks.get</code></p>
<p><code dir="ltr" translate="no">compute.reservationBlocks.list</code></p>
<p><code dir="ltr" translate="no">compute.reservationSubBlocks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  reservationSubBlocks.  get</code></li>
<li><code dir="ltr" translate="no">compute.  reservationSubBlocks.  list</code></li>
<li><code dir="ltr" translate="no">compute.  reservationSubBlocks.  performMaintenance</code></li>
<li><code dir="ltr" translate="no">compute.  reservationSubBlocks.  reportFaulty</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.reservations.get</code></p>
<p><code dir="ltr" translate="no">compute.reservations.list</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.resourcePolicies.get</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.resourcePolicies.list</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  update</code></li>
<li><code dir="ltr" translate="no">compute.resourcePolicies.use</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.routers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.routers.create</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.routers.delete</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  deleteRoutePolicy</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.routers.get</code></li>
<li><code dir="ltr" translate="no">compute.routers.getRoutePolicy</code></li>
<li><code dir="ltr" translate="no">compute.routers.list</code></li>
<li><code dir="ltr" translate="no">compute.routers.listBgpRoutes</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  listRoutePolicies</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.routers.update</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  updateRoutePolicy</code></li>
<li><code dir="ltr" translate="no">compute.routers.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.routes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.routes.create</code></li>
<li><code dir="ltr" translate="no">compute.  routes.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.routes.delete</code></li>
<li><code dir="ltr" translate="no">compute.  routes.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.routes.get</code></li>
<li><code dir="ltr" translate="no">compute.routes.list</code></li>
<li><code dir="ltr" translate="no">compute.  routes.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.routes.listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.securityPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.securityPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.securityPolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.serviceAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  create</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.serviceAttachments.get</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  list</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  update</code></li>
<li><code dir="ltr" translate="no">compute.serviceAttachments.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.snapshotGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.snapshotGroups.create</code></li>
<li><code dir="ltr" translate="no">compute.snapshotGroups.delete</code></li>
<li><code dir="ltr" translate="no">compute.snapshotGroups.get</code></li>
<li><code dir="ltr" translate="no">compute.  snapshotGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.snapshotGroups.list</code></li>
<li><code dir="ltr" translate="no">compute.  snapshotGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  snapshotGroups.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.snapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.snapshots.create</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.delete</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.get</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.list</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.updateKmsKey</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.spotAssistants.get</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.get</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.list</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.sslPolicies.create</code></li>
<li><code dir="ltr" translate="no">compute.  sslPolicies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.sslPolicies.delete</code></li>
<li><code dir="ltr" translate="no">compute.  sslPolicies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.sslPolicies.get</code></li>
<li><code dir="ltr" translate="no">compute.sslPolicies.list</code></li>
<li><code dir="ltr" translate="no">compute.  sslPolicies.  listAvailableFeatures</code></li>
<li><code dir="ltr" translate="no">compute.  sslPolicies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  sslPolicies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.sslPolicies.update</code></li>
<li><code dir="ltr" translate="no">compute.sslPolicies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.storagePools.get</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.list</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.use</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.subnetworks.create</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.subnetworks.delete</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  expandIpCidrRange</code></li>
<li><code dir="ltr" translate="no">compute.subnetworks.get</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.subnetworks.list</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.subnetworks.mirror</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  setPrivateIpGoogleAccess</code></li>
<li><code dir="ltr" translate="no">compute.subnetworks.update</code></li>
<li><code dir="ltr" translate="no">compute.subnetworks.use</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  usePeerMigration</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetGrpcProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.targetGrpcProxies.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetGrpcProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  setUrlMap</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpsProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setCertificateMap</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setQuicOverride</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setSslCertificates</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setSslPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setUrlMap</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpsProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetInstances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.targetInstances.create</code></li>
<li><code dir="ltr" translate="no">compute.  targetInstances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetInstances.delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetInstances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetInstances.get</code></li>
<li><code dir="ltr" translate="no">compute.targetInstances.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetInstances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetInstances.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetInstances.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.targetInstances.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetPools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetPools.  addHealthCheck</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  addInstance</code></li>
<li><code dir="ltr" translate="no">compute.targetPools.create</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetPools.delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetPools.get</code></li>
<li><code dir="ltr" translate="no">compute.targetPools.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  removeHealthCheck</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  removeInstance</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.targetPools.update</code></li>
<li><code dir="ltr" translate="no">compute.targetPools.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetSslProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetSslProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.targetSslProxies.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  setBackendService</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  setCertificateMap</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  setProxyHeader</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  setSslCertificates</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  setSslPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetSslProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  attach</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetTcpProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.targetTcpProxies.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetTcpProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetVpnGateways.get</code></li>
<li><code dir="ltr" translate="no">compute.targetVpnGateways.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.targetVpnGateways.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.urlMaps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.urlMaps.create</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.delete</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.get</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  invalidateCache</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.list</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.update</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.use</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.validate</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.vpnGateways.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.vpnGateways.create</code></li>
<li><code dir="ltr" translate="no">compute.  vpnGateways.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.vpnGateways.delete</code></li>
<li><code dir="ltr" translate="no">compute.  vpnGateways.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.vpnGateways.get</code></li>
<li><code dir="ltr" translate="no">compute.vpnGateways.list</code></li>
<li><code dir="ltr" translate="no">compute.  vpnGateways.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  vpnGateways.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.vpnGateways.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.vpnGateways.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.vpnTunnels.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.vpnTunnels.create</code></li>
<li><code dir="ltr" translate="no">compute.  vpnTunnels.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.vpnTunnels.delete</code></li>
<li><code dir="ltr" translate="no">compute.  vpnTunnels.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.vpnTunnels.get</code></li>
<li><code dir="ltr" translate="no">compute.vpnTunnels.list</code></li>
<li><code dir="ltr" translate="no">compute.  vpnTunnels.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  vpnTunnels.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.vpnTunnels.setLabels</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.wireGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.wireGroups.create</code></li>
<li><code dir="ltr" translate="no">compute.wireGroups.delete</code></li>
<li><code dir="ltr" translate="no">compute.wireGroups.get</code></li>
<li><code dir="ltr" translate="no">compute.wireGroups.list</code></li>
<li><code dir="ltr" translate="no">compute.wireGroups.update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">container.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.apiServices.create</code></li>
<li><code dir="ltr" translate="no">container.apiServices.delete</code></li>
<li><code dir="ltr" translate="no">container.apiServices.get</code></li>
<li><code dir="ltr" translate="no">container.  apiServices.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.apiServices.list</code></li>
<li><code dir="ltr" translate="no">container.apiServices.update</code></li>
<li><code dir="ltr" translate="no">container.  apiServices.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.create</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.delete</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.get</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.list</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.update</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  update</code></li>
<li><code dir="ltr" translate="no">container.bindings.create</code></li>
<li><code dir="ltr" translate="no">container.bindings.delete</code></li>
<li><code dir="ltr" translate="no">container.bindings.get</code></li>
<li><code dir="ltr" translate="no">container.bindings.list</code></li>
<li><code dir="ltr" translate="no">container.bindings.update</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  approve</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  create</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  delete</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  get</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  list</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  update</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  create</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  get</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  list</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  update</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.bind</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.create</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoles.  escalate</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.get</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.list</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.update</code></li>
<li><code dir="ltr" translate="no">container.clusters.connect</code></li>
<li><code dir="ltr" translate="no">container.clusters.create</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">container.clusters.delete</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">container.clusters.get</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  getCredentials</code></li>
<li><code dir="ltr" translate="no">container.clusters.impersonate</code></li>
<li><code dir="ltr" translate="no">container.clusters.list</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">container.clusters.update</code></li>
<li><code dir="ltr" translate="no">container.  componentStatuses.  get</code></li>
<li><code dir="ltr" translate="no">container.  componentStatuses.  list</code></li>
<li><code dir="ltr" translate="no">container.configMaps.create</code></li>
<li><code dir="ltr" translate="no">container.configMaps.delete</code></li>
<li><code dir="ltr" translate="no">container.configMaps.get</code></li>
<li><code dir="ltr" translate="no">container.configMaps.list</code></li>
<li><code dir="ltr" translate="no">container.configMaps.update</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  create</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  get</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  list</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  update</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.create</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.delete</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.get</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.getStatus</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.list</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.update</code></li>
<li><code dir="ltr" translate="no">container.  cronJobs.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.create</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.delete</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.get</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.list</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.update</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.create</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.delete</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.get</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.list</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.update</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.create</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.delete</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.get</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.list</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.update</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  create</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  delete</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  get</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  update</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.create</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.delete</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.get</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.getStatus</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.list</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.update</code></li>
<li><code dir="ltr" translate="no">container.  daemonSets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.deployments.create</code></li>
<li><code dir="ltr" translate="no">container.deployments.delete</code></li>
<li><code dir="ltr" translate="no">container.deployments.get</code></li>
<li><code dir="ltr" translate="no">container.deployments.getScale</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.deployments.list</code></li>
<li><code dir="ltr" translate="no">container.deployments.rollback</code></li>
<li><code dir="ltr" translate="no">container.deployments.update</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  create</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  delete</code></li>
<li><code dir="ltr" translate="no">container.endpointSlices.get</code></li>
<li><code dir="ltr" translate="no">container.endpointSlices.list</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  update</code></li>
<li><code dir="ltr" translate="no">container.endpoints.create</code></li>
<li><code dir="ltr" translate="no">container.endpoints.delete</code></li>
<li><code dir="ltr" translate="no">container.endpoints.get</code></li>
<li><code dir="ltr" translate="no">container.endpoints.list</code></li>
<li><code dir="ltr" translate="no">container.endpoints.update</code></li>
<li><code dir="ltr" translate="no">container.events.create</code></li>
<li><code dir="ltr" translate="no">container.events.delete</code></li>
<li><code dir="ltr" translate="no">container.events.get</code></li>
<li><code dir="ltr" translate="no">container.events.list</code></li>
<li><code dir="ltr" translate="no">container.events.update</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.frontendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.frontendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  update</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  create</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  delete</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  get</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  list</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  update</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.hostServiceAgent.use</code></li>
<li><code dir="ltr" translate="no">container.ingresses.create</code></li>
<li><code dir="ltr" translate="no">container.ingresses.delete</code></li>
<li><code dir="ltr" translate="no">container.ingresses.get</code></li>
<li><code dir="ltr" translate="no">container.ingresses.getStatus</code></li>
<li><code dir="ltr" translate="no">container.ingresses.list</code></li>
<li><code dir="ltr" translate="no">container.ingresses.update</code></li>
<li><code dir="ltr" translate="no">container.  ingresses.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  update</code></li>
<li><code dir="ltr" translate="no">container.jobs.create</code></li>
<li><code dir="ltr" translate="no">container.jobs.delete</code></li>
<li><code dir="ltr" translate="no">container.jobs.get</code></li>
<li><code dir="ltr" translate="no">container.jobs.getStatus</code></li>
<li><code dir="ltr" translate="no">container.jobs.list</code></li>
<li><code dir="ltr" translate="no">container.jobs.update</code></li>
<li><code dir="ltr" translate="no">container.jobs.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.leases.create</code></li>
<li><code dir="ltr" translate="no">container.leases.delete</code></li>
<li><code dir="ltr" translate="no">container.leases.get</code></li>
<li><code dir="ltr" translate="no">container.leases.list</code></li>
<li><code dir="ltr" translate="no">container.leases.update</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.create</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.delete</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.get</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.list</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.update</code></li>
<li><code dir="ltr" translate="no">container.  localSubjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  localSubjectAccessReviews.  list</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  create</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  delete</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  get</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  list</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  update</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  update</code></li>
<li><code dir="ltr" translate="no">container.namespaces.create</code></li>
<li><code dir="ltr" translate="no">container.namespaces.delete</code></li>
<li><code dir="ltr" translate="no">container.namespaces.finalize</code></li>
<li><code dir="ltr" translate="no">container.namespaces.get</code></li>
<li><code dir="ltr" translate="no">container.namespaces.getStatus</code></li>
<li><code dir="ltr" translate="no">container.namespaces.list</code></li>
<li><code dir="ltr" translate="no">container.namespaces.update</code></li>
<li><code dir="ltr" translate="no">container.  namespaces.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  create</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">container.networkPolicies.get</code></li>
<li><code dir="ltr" translate="no">container.networkPolicies.list</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  update</code></li>
<li><code dir="ltr" translate="no">container.nodes.create</code></li>
<li><code dir="ltr" translate="no">container.nodes.delete</code></li>
<li><code dir="ltr" translate="no">container.nodes.get</code></li>
<li><code dir="ltr" translate="no">container.nodes.getStatus</code></li>
<li><code dir="ltr" translate="no">container.nodes.list</code></li>
<li><code dir="ltr" translate="no">container.nodes.proxy</code></li>
<li><code dir="ltr" translate="no">container.nodes.update</code></li>
<li><code dir="ltr" translate="no">container.nodes.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.operations.get</code></li>
<li><code dir="ltr" translate="no">container.operations.list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  create</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  delete</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  get</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  update</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  create</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  delete</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  get</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  update</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.petSets.create</code></li>
<li><code dir="ltr" translate="no">container.petSets.delete</code></li>
<li><code dir="ltr" translate="no">container.petSets.get</code></li>
<li><code dir="ltr" translate="no">container.petSets.list</code></li>
<li><code dir="ltr" translate="no">container.petSets.update</code></li>
<li><code dir="ltr" translate="no">container.petSets.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  create</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  delete</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  get</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  list</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  update</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.podPresets.create</code></li>
<li><code dir="ltr" translate="no">container.podPresets.delete</code></li>
<li><code dir="ltr" translate="no">container.podPresets.get</code></li>
<li><code dir="ltr" translate="no">container.podPresets.list</code></li>
<li><code dir="ltr" translate="no">container.podPresets.update</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  create</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  get</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  list</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  update</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  use</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.create</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.delete</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.get</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.list</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.update</code></li>
<li><code dir="ltr" translate="no">container.pods.attach</code></li>
<li><code dir="ltr" translate="no">container.pods.create</code></li>
<li><code dir="ltr" translate="no">container.pods.delete</code></li>
<li><code dir="ltr" translate="no">container.pods.evict</code></li>
<li><code dir="ltr" translate="no">container.pods.exec</code></li>
<li><code dir="ltr" translate="no">container.pods.get</code></li>
<li><code dir="ltr" translate="no">container.pods.getLogs</code></li>
<li><code dir="ltr" translate="no">container.pods.getStatus</code></li>
<li><code dir="ltr" translate="no">container.pods.initialize</code></li>
<li><code dir="ltr" translate="no">container.pods.list</code></li>
<li><code dir="ltr" translate="no">container.pods.portForward</code></li>
<li><code dir="ltr" translate="no">container.pods.proxy</code></li>
<li><code dir="ltr" translate="no">container.pods.update</code></li>
<li><code dir="ltr" translate="no">container.pods.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.priorityClasses.get</code></li>
<li><code dir="ltr" translate="no">container.priorityClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.create</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.delete</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.get</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.getScale</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.list</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.update</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  create</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  delete</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  get</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  getScale</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  list</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  update</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  create</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  delete</code></li>
<li><code dir="ltr" translate="no">container.resourceQuotas.get</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.resourceQuotas.list</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  update</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.create</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.delete</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.get</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.list</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.update</code></li>
<li><code dir="ltr" translate="no">container.roles.bind</code></li>
<li><code dir="ltr" translate="no">container.roles.create</code></li>
<li><code dir="ltr" translate="no">container.roles.delete</code></li>
<li><code dir="ltr" translate="no">container.roles.escalate</code></li>
<li><code dir="ltr" translate="no">container.roles.get</code></li>
<li><code dir="ltr" translate="no">container.roles.list</code></li>
<li><code dir="ltr" translate="no">container.roles.update</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.runtimeClasses.get</code></li>
<li><code dir="ltr" translate="no">container.runtimeClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.create</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.delete</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.get</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.list</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.update</code></li>
<li><code dir="ltr" translate="no">container.  scheduledJobs.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.secrets.create</code></li>
<li><code dir="ltr" translate="no">container.secrets.delete</code></li>
<li><code dir="ltr" translate="no">container.secrets.get</code></li>
<li><code dir="ltr" translate="no">container.secrets.list</code></li>
<li><code dir="ltr" translate="no">container.secrets.update</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.  list</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectRulesReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  create</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  createToken</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  delete</code></li>
<li><code dir="ltr" translate="no">container.serviceAccounts.get</code></li>
<li><code dir="ltr" translate="no">container.serviceAccounts.list</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  update</code></li>
<li><code dir="ltr" translate="no">container.services.create</code></li>
<li><code dir="ltr" translate="no">container.services.delete</code></li>
<li><code dir="ltr" translate="no">container.services.get</code></li>
<li><code dir="ltr" translate="no">container.services.getStatus</code></li>
<li><code dir="ltr" translate="no">container.services.list</code></li>
<li><code dir="ltr" translate="no">container.services.proxy</code></li>
<li><code dir="ltr" translate="no">container.services.update</code></li>
<li><code dir="ltr" translate="no">container.  services.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.create</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.delete</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.get</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  getScale</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.list</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.update</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.storageClasses.get</code></li>
<li><code dir="ltr" translate="no">container.storageClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.storageStates.create</code></li>
<li><code dir="ltr" translate="no">container.storageStates.delete</code></li>
<li><code dir="ltr" translate="no">container.storageStates.get</code></li>
<li><code dir="ltr" translate="no">container.  storageStates.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.storageStates.list</code></li>
<li><code dir="ltr" translate="no">container.storageStates.update</code></li>
<li><code dir="ltr" translate="no">container.  storageStates.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  create</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  get</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  list</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  update</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  subjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  subjectAccessReviews.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  update</code></li>
<li><code dir="ltr" translate="no">container.tokenReviews.create</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.create</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.delete</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.get</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.list</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.update</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  delete</code></li>
<li><code dir="ltr" translate="no">container.volumeSnapshots.get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.volumeSnapshots.list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  create</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  delete</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  list</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  cancelPreview</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  create</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  delete</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  stop</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  update</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.manifests.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  manifests.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  manifests.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.resources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  resources.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  resources.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  getType</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  listTypes</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.types.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.types.create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.managedZones.get</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getOpenIdToken</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">logging.buckets.create</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">logging.buckets.delete</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">logging.buckets.get</code></p>
<p><code dir="ltr" translate="no">logging.buckets.list</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">logging.buckets.undelete</code></p>
<p><code dir="ltr" translate="no">logging.buckets.update</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.exclusions.create</code></li>
<li><code dir="ltr" translate="no">logging.exclusions.delete</code></li>
<li><code dir="ltr" translate="no">logging.exclusions.get</code></li>
<li><code dir="ltr" translate="no">logging.exclusions.list</code></li>
<li><code dir="ltr" translate="no">logging.exclusions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.links.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.links.create</code></li>
<li><code dir="ltr" translate="no">logging.links.delete</code></li>
<li><code dir="ltr" translate="no">logging.links.get</code></li>
<li><code dir="ltr" translate="no">logging.links.list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.locations.get</code></li>
<li><code dir="ltr" translate="no">logging.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.logMetrics.create</code></li>
<li><code dir="ltr" translate="no">logging.logMetrics.delete</code></li>
<li><code dir="ltr" translate="no">logging.logMetrics.get</code></li>
<li><code dir="ltr" translate="no">logging.logMetrics.list</code></li>
<li><code dir="ltr" translate="no">logging.logMetrics.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logScopes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.logScopes.create</code></li>
<li><code dir="ltr" translate="no">logging.logScopes.delete</code></li>
<li><code dir="ltr" translate="no">logging.logScopes.get</code></li>
<li><code dir="ltr" translate="no">logging.logScopes.list</code></li>
<li><code dir="ltr" translate="no">logging.logScopes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logServiceIndexes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServices.list</code></p>
<p><code dir="ltr" translate="no">logging.logs.list</code></p>
<p><code dir="ltr" translate="no">logging.notificationRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.  notificationRules.  create</code></li>
<li><code dir="ltr" translate="no">logging.  notificationRules.  delete</code></li>
<li><code dir="ltr" translate="no">logging.notificationRules.get</code></li>
<li><code dir="ltr" translate="no">logging.notificationRules.list</code></li>
<li><code dir="ltr" translate="no">logging.  notificationRules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.operations.cancel</code></li>
<li><code dir="ltr" translate="no">logging.operations.get</code></li>
<li><code dir="ltr" translate="no">logging.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.settings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.settings.get</code></li>
<li><code dir="ltr" translate="no">logging.settings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.sinks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.sinks.create</code></li>
<li><code dir="ltr" translate="no">logging.sinks.delete</code></li>
<li><code dir="ltr" translate="no">logging.sinks.get</code></li>
<li><code dir="ltr" translate="no">logging.sinks.list</code></li>
<li><code dir="ltr" translate="no">logging.sinks.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.sqlAlerts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.sqlAlerts.create</code></li>
<li><code dir="ltr" translate="no">logging.sqlAlerts.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.views.create</code></p>
<p><code dir="ltr" translate="no">logging.views.delete</code></p>
<p><code dir="ltr" translate="no">logging.views.get</code></p>
<p><code dir="ltr" translate="no">logging.views.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">logging.views.list</code></p>
<p><code dir="ltr" translate="no">logging.views.update</code></p>
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
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  create</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  list</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  locations.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  operations.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  list</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  regionalEndpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  regionalEndpoints.  create</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  regionalEndpoints.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  regionalEndpoints.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  regionalEndpoints.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  create</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  list</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  update</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.  create</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.  list</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  addressGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.locations.get</code></li>
<li><code dir="ltr" translate="no">networksecurity.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">networksecurity.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.operations.get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  sacAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  sacAttachments.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  sacAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  sacAttachments.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  sacAttachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.sacRealms.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  sacRealms.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  sacRealms.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.sacRealms.get</code></li>
<li><code dir="ltr" translate="no">networksecurity.sacRealms.list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  securityProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  securityProfiles.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfiles.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfiles.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfiles.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfiles.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfiles.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.urlLists.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  urlLists.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  urlLists.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.urlLists.get</code></li>
<li><code dir="ltr" translate="no">networksecurity.urlLists.list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  urlLists.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.urlLists.use</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  agentGateways.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  agentGateways.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  agentGateways.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  agentGateways.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  agentGateways.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  agentGateways.  use</code></li>
<li><code dir="ltr" translate="no">networkservices.  authzExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  authzExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  authzExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  authzExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  authzExtensions.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  authzExtensions.  use</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.gateways.get</code></li>
<li><code dir="ltr" translate="no">networkservices.gateways.list</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.gateways.use</code></li>
<li><code dir="ltr" translate="no">networkservices.  googleTagGatewayPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  googleTagGatewayPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  googleTagGatewayPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  googleTagGatewayPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  googleTagGatewayPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  grpcRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  grpcRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.grpcRoutes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.  grpcRoutes.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  grpcRoutes.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.httpRoutes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpRoutes.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpRoutes.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  use</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTcpExtensions.  createForNetwork</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTcpExtensions.  deleteForNetwork</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTcpExtensions.  getForNetwork</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTcpExtensions.  listForNetwork</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTcpExtensions.  updateForNetwork</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.locations.get</code></li>
<li><code dir="ltr" translate="no">networkservices.locations.list</code></li>
<li><code dir="ltr" translate="no">networkservices.meshes.create</code></li>
<li><code dir="ltr" translate="no">networkservices.  meshes.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.meshes.delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  meshes.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.meshes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.meshes.list</code></li>
<li><code dir="ltr" translate="no">networkservices.  meshes.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">networkservices.  meshes.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">networkservices.meshes.update</code></li>
<li><code dir="ltr" translate="no">networkservices.meshes.use</code></li>
<li><code dir="ltr" translate="no">networkservices.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">networkservices.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.operations.get</code></li>
<li><code dir="ltr" translate="no">networkservices.  operations.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  route_views.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  route_views.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceBindings.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceBindings.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceBindings.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceBindings.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceBindings.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  tcpRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  tcpRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.tcpRoutes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.tcpRoutes.list</code></li>
<li><code dir="ltr" translate="no">networkservices.  tcpRoutes.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  tlsRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  tlsRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.tlsRoutes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.tlsRoutes.list</code></li>
<li><code dir="ltr" translate="no">networkservices.  tlsRoutes.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.scopes.get</code></p>
<p><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">pubsub.  messageTransforms.  validate</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">pubsub.schemas.attach</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.commit</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.create</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.delete</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.get</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.list</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.listRevisions</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.rollback</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.validate</code></li>
</ul>
<p><code dir="ltr" translate="no">pubsub.snapshots.create</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.get</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.seek</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.update</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.update</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  detachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.update</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.updateTag</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  update</code></li>
</ul>
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
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  update</code></li>
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
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  delete</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  delete</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  operations.  get</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  addPeering</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  createPeeredDnsDomain</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  deleteConnection</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  deletePeeredDnsDomain</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  disableVpcServiceControls</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  enableVpcServiceControls</code></p>
<p><code dir="ltr" translate="no">servicenetworking.services.get</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  getVpcServiceControls</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  listPeeredDnsDomains</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p>
<p><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  list</code></p>
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
</ul>
<p><code dir="ltr" translate="no">trafficdirector.*</code></p>
<ul>
<li><code dir="ltr" translate="no">trafficdirector.  networks.  getConfigs</code></li>
<li><code dir="ltr" translate="no">trafficdirector.  networks.  reportMetrics</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Managed Service for Apache Airflow permissions

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
<td><h4 id="composer.dags.execute" class="permission-name add-link" data-text="composer.dags.execute" tabindex="-1"><code dir="ltr" translate="no">composer.dags.execute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.dags.get" class="permission-name add-link" data-text="composer.dags.get" tabindex="-1"><code dir="ltr" translate="no">composer.dags.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="composer.dags.getSourceCode" class="permission-name add-link" data-text="composer.dags.getSourceCode" tabindex="-1"><code dir="ltr" translate="no">composer.dags.getSourceCode</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.dags.list" class="permission-name add-link" data-text="composer.dags.list" tabindex="-1"><code dir="ltr" translate="no">composer.dags.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.environments.create" class="permission-name add-link" data-text="composer.environments.create" tabindex="-1"><code dir="ltr" translate="no">composer.environments.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.environments.createTagBinding" class="permission-name add-link" data-text="composer.environments.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">composer.  environments.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.environments.delete" class="permission-name add-link" data-text="composer.environments.delete" tabindex="-1"><code dir="ltr" translate="no">composer.environments.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.environments.deleteTagBinding" class="permission-name add-link" data-text="composer.environments.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">composer.  environments.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.environments.executeAirflowCommand" class="permission-name add-link" data-text="composer.environments.executeAirflowCommand" tabindex="-1"><code dir="ltr" translate="no">composer.  environments.  executeAirflowCommand</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.environments.get" class="permission-name add-link" data-text="composer.environments.get" tabindex="-1"><code dir="ltr" translate="no">composer.environments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="composer.environments.list" class="permission-name add-link" data-text="composer.environments.list" tabindex="-1"><code dir="ltr" translate="no">composer.environments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.environments.listEffectiveTags" class="permission-name add-link" data-text="composer.environments.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">composer.  environments.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.environments.listTagBindings" class="permission-name add-link" data-text="composer.environments.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">composer.  environments.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.environments.update" class="permission-name add-link" data-text="composer.environments.update" tabindex="-1"><code dir="ltr" translate="no">composer.environments.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.imageversions.list" class="permission-name add-link" data-text="composer.imageversions.list" tabindex="-1"><code dir="ltr" translate="no">composer.imageversions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.operations.delete" class="permission-name add-link" data-text="composer.operations.delete" tabindex="-1"><code dir="ltr" translate="no">composer.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.operations.get" class="permission-name add-link" data-text="composer.operations.get" tabindex="-1"><code dir="ltr" translate="no">composer.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.operations.list" class="permission-name add-link" data-text="composer.operations.list" tabindex="-1"><code dir="ltr" translate="no">composer.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.userworkloadsconfigmaps.create" class="permission-name add-link" data-text="composer.userworkloadsconfigmaps.create" tabindex="-1"><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.userworkloadsconfigmaps.delete" class="permission-name add-link" data-text="composer.userworkloadsconfigmaps.delete" tabindex="-1"><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.userworkloadsconfigmaps.get" class="permission-name add-link" data-text="composer.userworkloadsconfigmaps.get" tabindex="-1"><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.userworkloadsconfigmaps.list" class="permission-name add-link" data-text="composer.userworkloadsconfigmaps.list" tabindex="-1"><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.userworkloadsconfigmaps.update" class="permission-name add-link" data-text="composer.userworkloadsconfigmaps.update" tabindex="-1"><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.userworkloadssecrets.create" class="permission-name add-link" data-text="composer.userworkloadssecrets.create" tabindex="-1"><code dir="ltr" translate="no">composer.  userworkloadssecrets.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.userworkloadssecrets.delete" class="permission-name add-link" data-text="composer.userworkloadssecrets.delete" tabindex="-1"><code dir="ltr" translate="no">composer.  userworkloadssecrets.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.userworkloadssecrets.get" class="permission-name add-link" data-text="composer.userworkloadssecrets.get" tabindex="-1"><code dir="ltr" translate="no">composer.  userworkloadssecrets.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="composer.userworkloadssecrets.list" class="permission-name add-link" data-text="composer.userworkloadssecrets.list" tabindex="-1"><code dir="ltr" translate="no">composer.  userworkloadssecrets.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="composer.userworkloadssecrets.update" class="permission-name add-link" data-text="composer.userworkloadssecrets.update" tabindex="-1"><code dir="ltr" translate="no">composer.  userworkloadssecrets.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
</tbody>
</table>
