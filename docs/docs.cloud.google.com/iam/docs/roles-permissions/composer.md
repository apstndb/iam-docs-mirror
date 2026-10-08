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
<td>Composer Administrator
<p>( <code>roles/ composer.admin</code> )</p>
<p>Provides full control of Managed Airflow resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>composer.*</code></p>
<ul>
<li><code>composer.dags.execute</code></li>
<li><code>composer.dags.get</code></li>
<li><code>composer.dags.getSourceCode</code></li>
<li><code>composer.dags.list</code></li>
<li><code>composer.environments.create</code></li>
<li><code>composer. environments. createTagBinding</code></li>
<li><code>composer.environments.delete</code></li>
<li><code>composer. environments. deleteTagBinding</code></li>
<li><code>composer. environments. executeAirflowCommand</code></li>
<li><code>composer.environments.get</code></li>
<li><code>composer.environments.list</code></li>
<li><code>composer. environments. listEffectiveTags</code></li>
<li><code>composer. environments. listTagBindings</code></li>
<li><code>composer.environments.update</code></li>
<li><code>composer.imageversions.list</code></li>
<li><code>composer.operations.delete</code></li>
<li><code>composer.operations.get</code></li>
<li><code>composer.operations.list</code></li>
<li><code>composer. userworkloadsconfigmaps. create</code></li>
<li><code>composer. userworkloadsconfigmaps. delete</code></li>
<li><code>composer. userworkloadsconfigmaps. get</code></li>
<li><code>composer. userworkloadsconfigmaps. list</code></li>
<li><code>composer. userworkloadsconfigmaps. update</code></li>
<li><code>composer. userworkloadssecrets. create</code></li>
<li><code>composer. userworkloadssecrets. delete</code></li>
<li><code>composer. userworkloadssecrets. get</code></li>
<li><code>composer. userworkloadssecrets. list</code></li>
<li><code>composer. userworkloadssecrets. update</code></li>
</ul>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Composer Editor
<p>( <code>roles/ composer.editor</code> )</p>
<p>Editor role for Composer</p></td>
<td><p><code>composer.dags.*</code></p>
<ul>
<li><code>composer.dags.execute</code></li>
<li><code>composer.dags.get</code></li>
<li><code>composer.dags.getSourceCode</code></li>
<li><code>composer.dags.list</code></li>
</ul>
<p><code>composer.environments.create</code></p>
<p><code>composer.environments.delete</code></p>
<p><code>composer. environments. executeAirflowCommand</code></p>
<p><code>composer.environments.get</code></p>
<p><code>composer.environments.list</code></p>
<p><code>composer. environments. listEffectiveTags</code></p>
<p><code>composer. environments. listTagBindings</code></p>
<p><code>composer.environments.update</code></p>
<p><code>composer.imageversions.list</code></p>
<p><code>composer.operations.*</code></p>
<ul>
<li><code>composer.operations.delete</code></li>
<li><code>composer.operations.get</code></li>
<li><code>composer.operations.list</code></li>
</ul>
<p><code>composer. userworkloadsconfigmaps.*</code></p>
<ul>
<li><code>composer. userworkloadsconfigmaps. create</code></li>
<li><code>composer. userworkloadsconfigmaps. delete</code></li>
<li><code>composer. userworkloadsconfigmaps. get</code></li>
<li><code>composer. userworkloadsconfigmaps. list</code></li>
<li><code>composer. userworkloadsconfigmaps. update</code></li>
</ul>
<p><code>composer. userworkloadssecrets.*</code></p>
<ul>
<li><code>composer. userworkloadssecrets. create</code></li>
<li><code>composer. userworkloadssecrets. delete</code></li>
<li><code>composer. userworkloadssecrets. get</code></li>
<li><code>composer. userworkloadssecrets. list</code></li>
<li><code>composer. userworkloadssecrets. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Composer User
<p>( <code>roles/ composer.user</code> )</p>
<p>Provides the permissions necessary to list and get Managed Airflow environments and operations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>composer.dags.*</code></p>
<ul>
<li><code>composer.dags.execute</code></li>
<li><code>composer.dags.get</code></li>
<li><code>composer.dags.getSourceCode</code></li>
<li><code>composer.dags.list</code></li>
</ul>
<p><code>composer.environments.get</code></p>
<p><code>composer.environments.list</code></p>
<p><code>composer.imageversions.list</code></p>
<p><code>composer.operations.get</code></p>
<p><code>composer.operations.list</code></p>
<p><code>composer. userworkloadsconfigmaps. get</code></p>
<p><code>composer. userworkloadsconfigmaps. list</code></p>
<p><code>composer. userworkloadssecrets. get</code></p>
<p><code>composer. userworkloadssecrets. list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Composer Viewer
<p>( <code>roles/ composer.viewer</code> )</p>
<p>Viewer role for Composer</p></td>
<td><p><code>composer.dags.get</code></p>
<p><code>composer.dags.getSourceCode</code></p>
<p><code>composer.dags.list</code></p>
<p><code>composer.environments.get</code></p>
<p><code>composer.environments.list</code></p>
<p><code>composer. environments. listEffectiveTags</code></p>
<p><code>composer. environments. listTagBindings</code></p>
<p><code>composer.imageversions.list</code></p>
<p><code>composer.operations.get</code></p>
<p><code>composer.operations.list</code></p>
<p><code>composer. userworkloadsconfigmaps. get</code></p>
<p><code>composer. userworkloadsconfigmaps. list</code></p>
<p><code>composer. userworkloadssecrets. get</code></p>
<p><code>composer. userworkloadssecrets. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud Composer v2 API Service Agent Extension
<p>( <code>roles/ composer.ServiceAgentV2Ext</code> )</p>
<p>Cloud Composer v2 API Service Agent Extension is a supplementary role required to manage Composer v2 environments.</p></td>
<td><p><code>iam. serviceAccounts. getIamPolicy</code></p>
<p><code>iam. serviceAccounts. setIamPolicy</code></p></td>
</tr>
<tr class="even">
<td>Environment and Storage Object Administrator
<p>( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p>Provides full control of Managed Airflow resources and of the objects in all project buckets.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>composer.*</code></p>
<ul>
<li><code>composer.dags.execute</code></li>
<li><code>composer.dags.get</code></li>
<li><code>composer.dags.getSourceCode</code></li>
<li><code>composer.dags.list</code></li>
<li><code>composer.environments.create</code></li>
<li><code>composer. environments. createTagBinding</code></li>
<li><code>composer.environments.delete</code></li>
<li><code>composer. environments. deleteTagBinding</code></li>
<li><code>composer. environments. executeAirflowCommand</code></li>
<li><code>composer.environments.get</code></li>
<li><code>composer.environments.list</code></li>
<li><code>composer. environments. listEffectiveTags</code></li>
<li><code>composer. environments. listTagBindings</code></li>
<li><code>composer.environments.update</code></li>
<li><code>composer.imageversions.list</code></li>
<li><code>composer.operations.delete</code></li>
<li><code>composer.operations.get</code></li>
<li><code>composer.operations.list</code></li>
<li><code>composer. userworkloadsconfigmaps. create</code></li>
<li><code>composer. userworkloadsconfigmaps. delete</code></li>
<li><code>composer. userworkloadsconfigmaps. get</code></li>
<li><code>composer. userworkloadsconfigmaps. list</code></li>
<li><code>composer. userworkloadsconfigmaps. update</code></li>
<li><code>composer. userworkloadssecrets. create</code></li>
<li><code>composer. userworkloadssecrets. delete</code></li>
<li><code>composer. userworkloadssecrets. get</code></li>
<li><code>composer. userworkloadssecrets. list</code></li>
<li><code>composer. userworkloadssecrets. update</code></li>
</ul>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
</ul>
<p><code>storage.managedFolders.create</code></p>
<p><code>storage.managedFolders.delete</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.managedFolders.update</code></p>
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
</ul></td>
</tr>
<tr class="odd">
<td>Environment and Storage Object User
<p>( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p>Read and use access to Cloud Composer resources and read access to Cloud Storage objects.</p></td>
<td><p><code>composer.dags.*</code></p>
<ul>
<li><code>composer.dags.execute</code></li>
<li><code>composer.dags.get</code></li>
<li><code>composer.dags.getSourceCode</code></li>
<li><code>composer.dags.list</code></li>
</ul>
<p><code>composer.environments.get</code></p>
<p><code>composer.environments.list</code></p>
<p><code>composer.imageversions.list</code></p>
<p><code>composer.operations.get</code></p>
<p><code>composer.operations.list</code></p>
<p><code>composer. userworkloadsconfigmaps. get</code></p>
<p><code>composer. userworkloadsconfigmaps. list</code></p>
<p><code>composer. userworkloadssecrets. get</code></p>
<p><code>composer. userworkloadssecrets. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td>Environment and Storage Object Viewer
<p>( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p>Provides the permissions necessary to list and get Managed Airflow environments and operations. Provides read-only access to objects in all project buckets.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>composer.dags.*</code></p>
<ul>
<li><code>composer.dags.execute</code></li>
<li><code>composer.dags.get</code></li>
<li><code>composer.dags.getSourceCode</code></li>
<li><code>composer.dags.list</code></li>
</ul>
<p><code>composer.environments.get</code></p>
<p><code>composer.environments.list</code></p>
<p><code>composer.imageversions.list</code></p>
<p><code>composer.operations.get</code></p>
<p><code>composer.operations.list</code></p>
<p><code>composer. userworkloadsconfigmaps. get</code></p>
<p><code>composer. userworkloadsconfigmaps. list</code></p>
<p><code>composer. userworkloadssecrets. get</code></p>
<p><code>composer. userworkloadssecrets. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td>Composer Shared VPC Agent
<p>( <code>roles/ composer.sharedVpcAgent</code> )</p>
<p>Role that should be assigned to Composer Agent service account in Shared VPC host project</p></td>
<td><p><code>compute. networkAttachments. create</code></p>
<p><code>compute. networkAttachments. delete</code></p>
<p><code>compute.networkAttachments.get</code></p>
<p><code>compute. networkAttachments. update</code></p>
<p><code>compute.networks.access</code></p>
<p><code>compute.networks.addPeering</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. networks. listPeeringRoutes</code></p>
<p><code>compute.networks.removePeering</code></p>
<p><code>compute.networks.updatePeering</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.networks.useExternalIp</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute. subnetworks. useExternalIp</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>dns.managedZones.get</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns. networks. targetWithPeeringZone</code></p></td>
</tr>
<tr class="even">
<td>Composer Worker
<p>( <code>roles/ composer.worker</code> )</p>
<p>Provides the permissions necessary to run a Managed Airflow environment VM. Intended for service accounts.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>artifactregistry.*</code></p>
<ul>
<li><code>artifactregistry. aptartifacts. create</code></li>
<li><code>artifactregistry. attachments. create</code></li>
<li><code>artifactregistry. attachments. delete</code></li>
<li><code>artifactregistry. attachments. get</code></li>
<li><code>artifactregistry. attachments. list</code></li>
<li><code>artifactregistry. dockerimages. get</code></li>
<li><code>artifactregistry. dockerimages. list</code></li>
<li><code>artifactregistry.files.delete</code></li>
<li><code>artifactregistry. files. download</code></li>
<li><code>artifactregistry.files.get</code></li>
<li><code>artifactregistry.files.list</code></li>
<li><code>artifactregistry.files.update</code></li>
<li><code>artifactregistry.files.upload</code></li>
<li><code>artifactregistry. kfpartifacts. create</code></li>
<li><code>artifactregistry.locations.get</code></li>
<li><code>artifactregistry. locations. list</code></li>
<li><code>artifactregistry. mavenartifacts. get</code></li>
<li><code>artifactregistry. mavenartifacts. list</code></li>
<li><code>artifactregistry. npmpackages. get</code></li>
<li><code>artifactregistry. npmpackages. list</code></li>
<li><code>artifactregistry. packages. delete</code></li>
<li><code>artifactregistry.packages.get</code></li>
<li><code>artifactregistry.packages.list</code></li>
<li><code>artifactregistry. packages. update</code></li>
<li><code>artifactregistry. projectconfigs. get</code></li>
<li><code>artifactregistry. projectconfigs. update</code></li>
<li><code>artifactregistry. projectsettings. get</code></li>
<li><code>artifactregistry. projectsettings. update</code></li>
<li><code>artifactregistry. pythonpackages. get</code></li>
<li><code>artifactregistry. pythonpackages. list</code></li>
<li><code>artifactregistry. repositories. create</code></li>
<li><code>artifactregistry. repositories. createOnPush</code></li>
<li><code>artifactregistry. repositories. createTagBinding</code></li>
<li><code>artifactregistry. repositories. delete</code></li>
<li><code>artifactregistry. repositories. deleteArtifacts</code></li>
<li><code>artifactregistry. repositories. deleteTagBinding</code></li>
<li><code>artifactregistry. repositories. downloadArtifacts</code></li>
<li><code>artifactregistry. repositories. exportArtifacts</code></li>
<li><code>artifactregistry. repositories. get</code></li>
<li><code>artifactregistry. repositories. getIamPolicy</code></li>
<li><code>artifactregistry. repositories. list</code></li>
<li><code>artifactregistry. repositories. listEffectiveTags</code></li>
<li><code>artifactregistry. repositories. listTagBindings</code></li>
<li><code>artifactregistry. repositories. readViaVirtualRepository</code></li>
<li><code>artifactregistry. repositories. setIamPolicy</code></li>
<li><code>artifactregistry. repositories. update</code></li>
<li><code>artifactregistry. repositories. uploadArtifacts</code></li>
<li><code>artifactregistry.rules.create</code></li>
<li><code>artifactregistry.rules.delete</code></li>
<li><code>artifactregistry.rules.get</code></li>
<li><code>artifactregistry.rules.list</code></li>
<li><code>artifactregistry.rules.update</code></li>
<li><code>artifactregistry.tags.create</code></li>
<li><code>artifactregistry.tags.delete</code></li>
<li><code>artifactregistry.tags.get</code></li>
<li><code>artifactregistry.tags.list</code></li>
<li><code>artifactregistry.tags.update</code></li>
<li><code>artifactregistry. versions. delete</code></li>
<li><code>artifactregistry.versions.get</code></li>
<li><code>artifactregistry.versions.list</code></li>
<li><code>artifactregistry. versions. update</code></li>
<li><code>artifactregistry. yumartifacts. create</code></li>
</ul>
<p><code>cloudbuild.builds.create</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild.builds.update</code></p>
<p><code>cloudbuild.locations.*</code></p>
<ul>
<li><code>cloudbuild.locations.get</code></li>
<li><code>cloudbuild.locations.list</code></li>
</ul>
<p><code>cloudbuild.operations.*</code></p>
<ul>
<li><code>cloudbuild.operations.get</code></li>
<li><code>cloudbuild.operations.list</code></li>
</ul>
<p><code>cloudbuild.workerpools.use</code></p>
<p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>composer.environments.get</code></p>
<p><code>compute.images.create</code></p>
<p><code>container.*</code></p>
<ul>
<li><code>container.apiServices.create</code></li>
<li><code>container.apiServices.delete</code></li>
<li><code>container.apiServices.get</code></li>
<li><code>container. apiServices. getStatus</code></li>
<li><code>container.apiServices.list</code></li>
<li><code>container.apiServices.update</code></li>
<li><code>container. apiServices. updateStatus</code></li>
<li><code>container.auditSinks.create</code></li>
<li><code>container.auditSinks.delete</code></li>
<li><code>container.auditSinks.get</code></li>
<li><code>container.auditSinks.list</code></li>
<li><code>container.auditSinks.update</code></li>
<li><code>container. backendConfigs. create</code></li>
<li><code>container. backendConfigs. delete</code></li>
<li><code>container.backendConfigs.get</code></li>
<li><code>container.backendConfigs.list</code></li>
<li><code>container. backendConfigs. update</code></li>
<li><code>container.bindings.create</code></li>
<li><code>container.bindings.delete</code></li>
<li><code>container.bindings.get</code></li>
<li><code>container.bindings.list</code></li>
<li><code>container.bindings.update</code></li>
<li><code>container. certificateSigningRequests. approve</code></li>
<li><code>container. certificateSigningRequests. create</code></li>
<li><code>container. certificateSigningRequests. delete</code></li>
<li><code>container. certificateSigningRequests. get</code></li>
<li><code>container. certificateSigningRequests. getStatus</code></li>
<li><code>container. certificateSigningRequests. list</code></li>
<li><code>container. certificateSigningRequests. update</code></li>
<li><code>container. certificateSigningRequests. updateStatus</code></li>
<li><code>container. clusterRoleBindings. create</code></li>
<li><code>container. clusterRoleBindings. delete</code></li>
<li><code>container. clusterRoleBindings. get</code></li>
<li><code>container. clusterRoleBindings. list</code></li>
<li><code>container. clusterRoleBindings. update</code></li>
<li><code>container.clusterRoles.bind</code></li>
<li><code>container.clusterRoles.create</code></li>
<li><code>container.clusterRoles.delete</code></li>
<li><code>container. clusterRoles. escalate</code></li>
<li><code>container.clusterRoles.get</code></li>
<li><code>container.clusterRoles.list</code></li>
<li><code>container.clusterRoles.update</code></li>
<li><code>container.clusters.connect</code></li>
<li><code>container.clusters.create</code></li>
<li><code>container. clusters. createTagBinding</code></li>
<li><code>container.clusters.delete</code></li>
<li><code>container. clusters. deleteTagBinding</code></li>
<li><code>container.clusters.get</code></li>
<li><code>container. clusters. getCredentials</code></li>
<li><code>container.clusters.impersonate</code></li>
<li><code>container.clusters.list</code></li>
<li><code>container. clusters. listEffectiveTags</code></li>
<li><code>container. clusters. listTagBindings</code></li>
<li><code>container.clusters.update</code></li>
<li><code>container. componentStatuses. get</code></li>
<li><code>container. componentStatuses. list</code></li>
<li><code>container.configMaps.create</code></li>
<li><code>container.configMaps.delete</code></li>
<li><code>container.configMaps.get</code></li>
<li><code>container.configMaps.list</code></li>
<li><code>container.configMaps.update</code></li>
<li><code>container. controllerRevisions. create</code></li>
<li><code>container. controllerRevisions. delete</code></li>
<li><code>container. controllerRevisions. get</code></li>
<li><code>container. controllerRevisions. list</code></li>
<li><code>container. controllerRevisions. update</code></li>
<li><code>container.cronJobs.create</code></li>
<li><code>container.cronJobs.delete</code></li>
<li><code>container.cronJobs.get</code></li>
<li><code>container.cronJobs.getStatus</code></li>
<li><code>container.cronJobs.list</code></li>
<li><code>container.cronJobs.update</code></li>
<li><code>container. cronJobs. updateStatus</code></li>
<li><code>container.csiDrivers.create</code></li>
<li><code>container.csiDrivers.delete</code></li>
<li><code>container.csiDrivers.get</code></li>
<li><code>container.csiDrivers.list</code></li>
<li><code>container.csiDrivers.update</code></li>
<li><code>container.csiNodeInfos.create</code></li>
<li><code>container.csiNodeInfos.delete</code></li>
<li><code>container.csiNodeInfos.get</code></li>
<li><code>container.csiNodeInfos.list</code></li>
<li><code>container.csiNodeInfos.update</code></li>
<li><code>container.csiNodes.create</code></li>
<li><code>container.csiNodes.delete</code></li>
<li><code>container.csiNodes.get</code></li>
<li><code>container.csiNodes.list</code></li>
<li><code>container.csiNodes.update</code></li>
<li><code>container. customResourceDefinitions. create</code></li>
<li><code>container. customResourceDefinitions. delete</code></li>
<li><code>container. customResourceDefinitions. get</code></li>
<li><code>container. customResourceDefinitions. getStatus</code></li>
<li><code>container. customResourceDefinitions. list</code></li>
<li><code>container. customResourceDefinitions. update</code></li>
<li><code>container. customResourceDefinitions. updateStatus</code></li>
<li><code>container.daemonSets.create</code></li>
<li><code>container.daemonSets.delete</code></li>
<li><code>container.daemonSets.get</code></li>
<li><code>container.daemonSets.getStatus</code></li>
<li><code>container.daemonSets.list</code></li>
<li><code>container.daemonSets.update</code></li>
<li><code>container. daemonSets. updateStatus</code></li>
<li><code>container.deployments.create</code></li>
<li><code>container.deployments.delete</code></li>
<li><code>container.deployments.get</code></li>
<li><code>container.deployments.getScale</code></li>
<li><code>container. deployments. getStatus</code></li>
<li><code>container.deployments.list</code></li>
<li><code>container.deployments.rollback</code></li>
<li><code>container.deployments.update</code></li>
<li><code>container. deployments. updateScale</code></li>
<li><code>container. deployments. updateStatus</code></li>
<li><code>container. endpointSlices. create</code></li>
<li><code>container. endpointSlices. delete</code></li>
<li><code>container.endpointSlices.get</code></li>
<li><code>container.endpointSlices.list</code></li>
<li><code>container. endpointSlices. update</code></li>
<li><code>container.endpoints.create</code></li>
<li><code>container.endpoints.delete</code></li>
<li><code>container.endpoints.get</code></li>
<li><code>container.endpoints.list</code></li>
<li><code>container.endpoints.update</code></li>
<li><code>container.events.create</code></li>
<li><code>container.events.delete</code></li>
<li><code>container.events.get</code></li>
<li><code>container.events.list</code></li>
<li><code>container.events.update</code></li>
<li><code>container. frontendConfigs. create</code></li>
<li><code>container. frontendConfigs. delete</code></li>
<li><code>container.frontendConfigs.get</code></li>
<li><code>container.frontendConfigs.list</code></li>
<li><code>container. frontendConfigs. update</code></li>
<li><code>container. horizontalPodAutoscalers. create</code></li>
<li><code>container. horizontalPodAutoscalers. delete</code></li>
<li><code>container. horizontalPodAutoscalers. get</code></li>
<li><code>container. horizontalPodAutoscalers. getStatus</code></li>
<li><code>container. horizontalPodAutoscalers. list</code></li>
<li><code>container. horizontalPodAutoscalers. update</code></li>
<li><code>container. horizontalPodAutoscalers. updateStatus</code></li>
<li><code>container.hostServiceAgent.use</code></li>
<li><code>container.ingresses.create</code></li>
<li><code>container.ingresses.delete</code></li>
<li><code>container.ingresses.get</code></li>
<li><code>container.ingresses.getStatus</code></li>
<li><code>container.ingresses.list</code></li>
<li><code>container.ingresses.update</code></li>
<li><code>container. ingresses. updateStatus</code></li>
<li><code>container. initializerConfigurations. create</code></li>
<li><code>container. initializerConfigurations. delete</code></li>
<li><code>container. initializerConfigurations. get</code></li>
<li><code>container. initializerConfigurations. list</code></li>
<li><code>container. initializerConfigurations. update</code></li>
<li><code>container.jobs.create</code></li>
<li><code>container.jobs.delete</code></li>
<li><code>container.jobs.get</code></li>
<li><code>container.jobs.getStatus</code></li>
<li><code>container.jobs.list</code></li>
<li><code>container.jobs.update</code></li>
<li><code>container.jobs.updateStatus</code></li>
<li><code>container.leases.create</code></li>
<li><code>container.leases.delete</code></li>
<li><code>container.leases.get</code></li>
<li><code>container.leases.list</code></li>
<li><code>container.leases.update</code></li>
<li><code>container.limitRanges.create</code></li>
<li><code>container.limitRanges.delete</code></li>
<li><code>container.limitRanges.get</code></li>
<li><code>container.limitRanges.list</code></li>
<li><code>container.limitRanges.update</code></li>
<li><code>container. localSubjectAccessReviews. create</code></li>
<li><code>container. localSubjectAccessReviews. list</code></li>
<li><code>container. managedCertificates. create</code></li>
<li><code>container. managedCertificates. delete</code></li>
<li><code>container. managedCertificates. get</code></li>
<li><code>container. managedCertificates. list</code></li>
<li><code>container. managedCertificates. update</code></li>
<li><code>container. mutatingWebhookConfigurations. create</code></li>
<li><code>container. mutatingWebhookConfigurations. delete</code></li>
<li><code>container. mutatingWebhookConfigurations. get</code></li>
<li><code>container. mutatingWebhookConfigurations. list</code></li>
<li><code>container. mutatingWebhookConfigurations. update</code></li>
<li><code>container.namespaces.create</code></li>
<li><code>container.namespaces.delete</code></li>
<li><code>container.namespaces.finalize</code></li>
<li><code>container.namespaces.get</code></li>
<li><code>container.namespaces.getStatus</code></li>
<li><code>container.namespaces.list</code></li>
<li><code>container.namespaces.update</code></li>
<li><code>container. namespaces. updateStatus</code></li>
<li><code>container. networkPolicies. create</code></li>
<li><code>container. networkPolicies. delete</code></li>
<li><code>container.networkPolicies.get</code></li>
<li><code>container.networkPolicies.list</code></li>
<li><code>container. networkPolicies. update</code></li>
<li><code>container.nodes.create</code></li>
<li><code>container.nodes.delete</code></li>
<li><code>container.nodes.get</code></li>
<li><code>container.nodes.getStatus</code></li>
<li><code>container.nodes.list</code></li>
<li><code>container.nodes.proxy</code></li>
<li><code>container.nodes.update</code></li>
<li><code>container.nodes.updateStatus</code></li>
<li><code>container.operations.get</code></li>
<li><code>container.operations.list</code></li>
<li><code>container. persistentVolumeClaims. create</code></li>
<li><code>container. persistentVolumeClaims. delete</code></li>
<li><code>container. persistentVolumeClaims. get</code></li>
<li><code>container. persistentVolumeClaims. getStatus</code></li>
<li><code>container. persistentVolumeClaims. list</code></li>
<li><code>container. persistentVolumeClaims. update</code></li>
<li><code>container. persistentVolumeClaims. updateStatus</code></li>
<li><code>container. persistentVolumes. create</code></li>
<li><code>container. persistentVolumes. delete</code></li>
<li><code>container. persistentVolumes. get</code></li>
<li><code>container. persistentVolumes. getStatus</code></li>
<li><code>container. persistentVolumes. list</code></li>
<li><code>container. persistentVolumes. update</code></li>
<li><code>container. persistentVolumes. updateStatus</code></li>
<li><code>container.petSets.create</code></li>
<li><code>container.petSets.delete</code></li>
<li><code>container.petSets.get</code></li>
<li><code>container.petSets.list</code></li>
<li><code>container.petSets.update</code></li>
<li><code>container.petSets.updateStatus</code></li>
<li><code>container. podDisruptionBudgets. create</code></li>
<li><code>container. podDisruptionBudgets. delete</code></li>
<li><code>container. podDisruptionBudgets. get</code></li>
<li><code>container. podDisruptionBudgets. getStatus</code></li>
<li><code>container. podDisruptionBudgets. list</code></li>
<li><code>container. podDisruptionBudgets. update</code></li>
<li><code>container. podDisruptionBudgets. updateStatus</code></li>
<li><code>container.podPresets.create</code></li>
<li><code>container.podPresets.delete</code></li>
<li><code>container.podPresets.get</code></li>
<li><code>container.podPresets.list</code></li>
<li><code>container.podPresets.update</code></li>
<li><code>container. podSecurityPolicies. create</code></li>
<li><code>container. podSecurityPolicies. delete</code></li>
<li><code>container. podSecurityPolicies. get</code></li>
<li><code>container. podSecurityPolicies. list</code></li>
<li><code>container. podSecurityPolicies. update</code></li>
<li><code>container. podSecurityPolicies. use</code></li>
<li><code>container.podTemplates.create</code></li>
<li><code>container.podTemplates.delete</code></li>
<li><code>container.podTemplates.get</code></li>
<li><code>container.podTemplates.list</code></li>
<li><code>container.podTemplates.update</code></li>
<li><code>container.pods.attach</code></li>
<li><code>container.pods.create</code></li>
<li><code>container.pods.delete</code></li>
<li><code>container.pods.evict</code></li>
<li><code>container.pods.exec</code></li>
<li><code>container.pods.get</code></li>
<li><code>container.pods.getLogs</code></li>
<li><code>container.pods.getStatus</code></li>
<li><code>container.pods.initialize</code></li>
<li><code>container.pods.list</code></li>
<li><code>container.pods.portForward</code></li>
<li><code>container.pods.proxy</code></li>
<li><code>container.pods.update</code></li>
<li><code>container.pods.updateStatus</code></li>
<li><code>container. priorityClasses. create</code></li>
<li><code>container. priorityClasses. delete</code></li>
<li><code>container.priorityClasses.get</code></li>
<li><code>container.priorityClasses.list</code></li>
<li><code>container. priorityClasses. update</code></li>
<li><code>container.replicaSets.create</code></li>
<li><code>container.replicaSets.delete</code></li>
<li><code>container.replicaSets.get</code></li>
<li><code>container.replicaSets.getScale</code></li>
<li><code>container. replicaSets. getStatus</code></li>
<li><code>container.replicaSets.list</code></li>
<li><code>container.replicaSets.update</code></li>
<li><code>container. replicaSets. updateScale</code></li>
<li><code>container. replicaSets. updateStatus</code></li>
<li><code>container. replicationControllers. create</code></li>
<li><code>container. replicationControllers. delete</code></li>
<li><code>container. replicationControllers. get</code></li>
<li><code>container. replicationControllers. getScale</code></li>
<li><code>container. replicationControllers. getStatus</code></li>
<li><code>container. replicationControllers. list</code></li>
<li><code>container. replicationControllers. update</code></li>
<li><code>container. replicationControllers. updateScale</code></li>
<li><code>container. replicationControllers. updateStatus</code></li>
<li><code>container. resourceQuotas. create</code></li>
<li><code>container. resourceQuotas. delete</code></li>
<li><code>container.resourceQuotas.get</code></li>
<li><code>container. resourceQuotas. getStatus</code></li>
<li><code>container.resourceQuotas.list</code></li>
<li><code>container. resourceQuotas. update</code></li>
<li><code>container. resourceQuotas. updateStatus</code></li>
<li><code>container.roleBindings.create</code></li>
<li><code>container.roleBindings.delete</code></li>
<li><code>container.roleBindings.get</code></li>
<li><code>container.roleBindings.list</code></li>
<li><code>container.roleBindings.update</code></li>
<li><code>container.roles.bind</code></li>
<li><code>container.roles.create</code></li>
<li><code>container.roles.delete</code></li>
<li><code>container.roles.escalate</code></li>
<li><code>container.roles.get</code></li>
<li><code>container.roles.list</code></li>
<li><code>container.roles.update</code></li>
<li><code>container. runtimeClasses. create</code></li>
<li><code>container. runtimeClasses. delete</code></li>
<li><code>container.runtimeClasses.get</code></li>
<li><code>container.runtimeClasses.list</code></li>
<li><code>container. runtimeClasses. update</code></li>
<li><code>container.scheduledJobs.create</code></li>
<li><code>container.scheduledJobs.delete</code></li>
<li><code>container.scheduledJobs.get</code></li>
<li><code>container.scheduledJobs.list</code></li>
<li><code>container.scheduledJobs.update</code></li>
<li><code>container. scheduledJobs. updateStatus</code></li>
<li><code>container.secrets.create</code></li>
<li><code>container.secrets.delete</code></li>
<li><code>container.secrets.get</code></li>
<li><code>container.secrets.list</code></li>
<li><code>container.secrets.update</code></li>
<li><code>container. selfSubjectAccessReviews. create</code></li>
<li><code>container. selfSubjectAccessReviews. list</code></li>
<li><code>container. selfSubjectRulesReviews. create</code></li>
<li><code>container. serviceAccounts. create</code></li>
<li><code>container. serviceAccounts. createToken</code></li>
<li><code>container. serviceAccounts. delete</code></li>
<li><code>container.serviceAccounts.get</code></li>
<li><code>container.serviceAccounts.list</code></li>
<li><code>container. serviceAccounts. update</code></li>
<li><code>container.services.create</code></li>
<li><code>container.services.delete</code></li>
<li><code>container.services.get</code></li>
<li><code>container.services.getStatus</code></li>
<li><code>container.services.list</code></li>
<li><code>container.services.proxy</code></li>
<li><code>container.services.update</code></li>
<li><code>container. services. updateStatus</code></li>
<li><code>container.statefulSets.create</code></li>
<li><code>container.statefulSets.delete</code></li>
<li><code>container.statefulSets.get</code></li>
<li><code>container. statefulSets. getScale</code></li>
<li><code>container. statefulSets. getStatus</code></li>
<li><code>container.statefulSets.list</code></li>
<li><code>container.statefulSets.update</code></li>
<li><code>container. statefulSets. updateScale</code></li>
<li><code>container. statefulSets. updateStatus</code></li>
<li><code>container. storageClasses. create</code></li>
<li><code>container. storageClasses. delete</code></li>
<li><code>container.storageClasses.get</code></li>
<li><code>container.storageClasses.list</code></li>
<li><code>container. storageClasses. update</code></li>
<li><code>container.storageStates.create</code></li>
<li><code>container.storageStates.delete</code></li>
<li><code>container.storageStates.get</code></li>
<li><code>container. storageStates. getStatus</code></li>
<li><code>container.storageStates.list</code></li>
<li><code>container.storageStates.update</code></li>
<li><code>container. storageStates. updateStatus</code></li>
<li><code>container. storageVersionMigrations. create</code></li>
<li><code>container. storageVersionMigrations. delete</code></li>
<li><code>container. storageVersionMigrations. get</code></li>
<li><code>container. storageVersionMigrations. getStatus</code></li>
<li><code>container. storageVersionMigrations. list</code></li>
<li><code>container. storageVersionMigrations. update</code></li>
<li><code>container. storageVersionMigrations. updateStatus</code></li>
<li><code>container. subjectAccessReviews. create</code></li>
<li><code>container. subjectAccessReviews. list</code></li>
<li><code>container. thirdPartyObjects. create</code></li>
<li><code>container. thirdPartyObjects. delete</code></li>
<li><code>container. thirdPartyObjects. get</code></li>
<li><code>container. thirdPartyObjects. list</code></li>
<li><code>container. thirdPartyObjects. update</code></li>
<li><code>container. thirdPartyResources. create</code></li>
<li><code>container. thirdPartyResources. delete</code></li>
<li><code>container. thirdPartyResources. get</code></li>
<li><code>container. thirdPartyResources. list</code></li>
<li><code>container. thirdPartyResources. update</code></li>
<li><code>container.tokenReviews.create</code></li>
<li><code>container.updateInfos.create</code></li>
<li><code>container.updateInfos.delete</code></li>
<li><code>container.updateInfos.get</code></li>
<li><code>container.updateInfos.list</code></li>
<li><code>container.updateInfos.update</code></li>
<li><code>container. validatingWebhookConfigurations. create</code></li>
<li><code>container. validatingWebhookConfigurations. delete</code></li>
<li><code>container. validatingWebhookConfigurations. get</code></li>
<li><code>container. validatingWebhookConfigurations. list</code></li>
<li><code>container. validatingWebhookConfigurations. update</code></li>
<li><code>container. volumeAttachments. create</code></li>
<li><code>container. volumeAttachments. delete</code></li>
<li><code>container. volumeAttachments. get</code></li>
<li><code>container. volumeAttachments. getStatus</code></li>
<li><code>container. volumeAttachments. list</code></li>
<li><code>container. volumeAttachments. update</code></li>
<li><code>container. volumeAttachments. updateStatus</code></li>
<li><code>container. volumeSnapshotClasses. create</code></li>
<li><code>container. volumeSnapshotClasses. delete</code></li>
<li><code>container. volumeSnapshotClasses. get</code></li>
<li><code>container. volumeSnapshotClasses. list</code></li>
<li><code>container. volumeSnapshotClasses. update</code></li>
<li><code>container. volumeSnapshotContents. create</code></li>
<li><code>container. volumeSnapshotContents. delete</code></li>
<li><code>container. volumeSnapshotContents. get</code></li>
<li><code>container. volumeSnapshotContents. getStatus</code></li>
<li><code>container. volumeSnapshotContents. list</code></li>
<li><code>container. volumeSnapshotContents. update</code></li>
<li><code>container. volumeSnapshotContents. updateStatus</code></li>
<li><code>container. volumeSnapshots. create</code></li>
<li><code>container. volumeSnapshots. delete</code></li>
<li><code>container.volumeSnapshots.get</code></li>
<li><code>container. volumeSnapshots. getStatus</code></li>
<li><code>container.volumeSnapshots.list</code></li>
<li><code>container. volumeSnapshots. update</code></li>
<li><code>container. volumeSnapshots. updateStatus</code></li>
</ul>
<p><code>containeranalysis. occurrences. create</code></p>
<p><code>containeranalysis. occurrences. delete</code></p>
<p><code>containeranalysis. occurrences. get</code></p>
<p><code>containeranalysis. occurrences. list</code></p>
<p><code>containeranalysis. occurrences. update</code></p>
<p><code>datalineage.events.create</code></p>
<p><code>datalineage. locations. processOpenLineageMessage</code></p>
<p><code>datalineage. processRevisions. insert</code></p>
<p><code>datalineage.processes.create</code></p>
<p><code>datalineage.processes.get</code></p>
<p><code>datalineage. processes. markAsDeleted</code></p>
<p><code>datalineage.processes.update</code></p>
<p><code>datalineage.runs.create</code></p>
<p><code>datalineage.runs.get</code></p>
<p><code>datalineage.runs.update</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.list</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>logging.views.access</code></p>
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
<p><code>pubsub. messageTransforms. validate</code></p>
<p><code>pubsub.schemas.attach</code></p>
<p><code>pubsub.schemas.commit</code></p>
<p><code>pubsub.schemas.create</code></p>
<p><code>pubsub.schemas.delete</code></p>
<p><code>pubsub.schemas.get</code></p>
<p><code>pubsub.schemas.getIamPolicy</code></p>
<p><code>pubsub.schemas.list</code></p>
<p><code>pubsub.schemas.listRevisions</code></p>
<p><code>pubsub.schemas.rollback</code></p>
<p><code>pubsub.schemas.validate</code></p>
<p><code>pubsub.snapshots.create</code></p>
<p><code>pubsub. snapshots. createTagBinding</code></p>
<p><code>pubsub.snapshots.delete</code></p>
<p><code>pubsub. snapshots. deleteTagBinding</code></p>
<p><code>pubsub.snapshots.get</code></p>
<p><code>pubsub.snapshots.list</code></p>
<p><code>pubsub. snapshots. listEffectiveTags</code></p>
<p><code>pubsub. snapshots. listTagBindings</code></p>
<p><code>pubsub.snapshots.seek</code></p>
<p><code>pubsub.snapshots.update</code></p>
<p><code>pubsub.subscriptions.consume</code></p>
<p><code>pubsub.subscriptions.create</code></p>
<p><code>pubsub. subscriptions. createTagBinding</code></p>
<p><code>pubsub.subscriptions.delete</code></p>
<p><code>pubsub. subscriptions. deleteTagBinding</code></p>
<p><code>pubsub.subscriptions.get</code></p>
<p><code>pubsub.subscriptions.list</code></p>
<p><code>pubsub. subscriptions. listEffectiveTags</code></p>
<p><code>pubsub. subscriptions. listTagBindings</code></p>
<p><code>pubsub.subscriptions.update</code></p>
<p><code>pubsub. topics. attachSubscription</code></p>
<p><code>pubsub.topics.create</code></p>
<p><code>pubsub.topics.createTagBinding</code></p>
<p><code>pubsub.topics.delete</code></p>
<p><code>pubsub.topics.deleteTagBinding</code></p>
<p><code>pubsub. topics. detachSubscription</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.list</code></p>
<p><code>pubsub. topics. listEffectiveTags</code></p>
<p><code>pubsub.topics.listTagBindings</code></p>
<p><code>pubsub.topics.publish</code></p>
<p><code>pubsub.topics.update</code></p>
<p><code>pubsub.topics.updateTag</code></p>
<p><code>recommender. containerDiagnosisInsights.*</code></p>
<ul>
<li><code>recommender. containerDiagnosisInsights. get</code></li>
<li><code>recommender. containerDiagnosisInsights. list</code></li>
<li><code>recommender. containerDiagnosisInsights. update</code></li>
</ul>
<p><code>recommender. containerDiagnosisRecommendations.*</code></p>
<ul>
<li><code>recommender. containerDiagnosisRecommendations. get</code></li>
<li><code>recommender. containerDiagnosisRecommendations. list</code></li>
<li><code>recommender. containerDiagnosisRecommendations. update</code></li>
</ul>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>recommender. networkAnalyzerGkeConnectivityInsights.*</code></p>
<ul>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. get</code></li>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. list</code></li>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. update</code></li>
</ul>
<p><code>recommender. networkAnalyzerGkeIpAddressInsights.*</code></p>
<ul>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. get</code></li>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. list</code></li>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. update</code></li>
</ul>
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>source.repos.get</code></p>
<p><code>source.repos.list</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
</ul>
<p><code>storage.managedFolders.create</code></p>
<p><code>storage.managedFolders.delete</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.managedFolders.update</code></p>
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
<td>Cloud Composer API Service Agent
<p>( <code>roles/ composer.serviceAgent</code> )</p>
<p>Cloud Composer API service agent can manage environments.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>appengine.applications.get</code></p>
<p><code>appengine. applications. listRuntimes</code></p>
<p><code>appengine.applications.update</code></p>
<p><code>appengine.instances.*</code></p>
<ul>
<li><code>appengine.instances.delete</code></li>
<li><code>appengine. instances. enableDebug</code></li>
<li><code>appengine.instances.get</code></li>
<li><code>appengine.instances.list</code></li>
</ul>
<p><code>appengine.memcache.addKey</code></p>
<p><code>appengine.memcache.flush</code></p>
<p><code>appengine.memcache.get</code></p>
<p><code>appengine.memcache.update</code></p>
<p><code>appengine.operations.*</code></p>
<ul>
<li><code>appengine.operations.get</code></li>
<li><code>appengine.operations.list</code></li>
</ul>
<p><code>appengine.runtimes.actAsAdmin</code></p>
<p><code>appengine.services.*</code></p>
<ul>
<li><code>appengine.services.delete</code></li>
<li><code>appengine.services.get</code></li>
<li><code>appengine.services.list</code></li>
<li><code>appengine.services.update</code></li>
</ul>
<p><code>appengine.versions.create</code></p>
<p><code>appengine.versions.delete</code></p>
<p><code>appengine. versions. exportAppImage</code></p>
<p><code>appengine.versions.get</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>appengine.versions.update</code></p>
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>artifactregistry. repositories. create</code></p>
<p><code>artifactregistry. repositories. delete</code></p>
<p><code>artifactregistry. repositories. deleteArtifacts</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>artifactregistry. repositories. update</code></p>
<p><code>artifactregistry. repositories. uploadArtifacts</code></p>
<p><code>artifactregistry.tags.get</code></p>
<p><code>backupdr. backupPlanAssociations. createForCloudSqlInstance</code></p>
<p><code>backupdr. backupPlanAssociations. createForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. createForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. deleteForCloudSqlInstance</code></p>
<p><code>backupdr. backupPlanAssociations. deleteForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. deleteForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. fetchForCloudSqlInstance</code></p>
<p><code>backupdr. backupPlanAssociations. fetchForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. getForCloudSqlInstance</code></p>
<p><code>backupdr. backupPlanAssociations. getForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. list</code></p>
<p><code>backupdr. backupPlanAssociations. triggerBackupForCloudSqlInstance</code></p>
<p><code>backupdr. backupPlanAssociations. triggerBackupForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. triggerBackupForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. updateForCloudSqlInstance</code></p>
<p><code>backupdr. backupPlanAssociations. updateForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. updateForComputeInstance</code></p>
<p><code>backupdr.backupPlans.get</code></p>
<p><code>backupdr.backupPlans.list</code></p>
<p><code>backupdr. backupPlans. useForCloudSqlInstance</code></p>
<p><code>backupdr. backupPlans. useForComputeDisk</code></p>
<p><code>backupdr. backupPlans. useForComputeInstance</code></p>
<p><code>backupdr.backupVaults.get</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr. bvbackups. fetchForCloudSqlInstance</code></p>
<p><code>backupdr. bvbackups. useReadOnlyForCloudSqlInstance</code></p>
<p><code>backupdr. bvdataSources. useReadOnlyForCloudSqlInstance</code></p>
<p><code>backupdr. dataSourceReferences. fetchForCloudSqlInstance</code></p>
<p><code>backupdr. dataSourceReferences. getForCloudSqlInstance</code></p>
<p><code>backupdr.locations.list</code></p>
<p><code>backupdr.operations.get</code></p>
<p><code>backupdr.operations.list</code></p>
<p><code>backupdr. serviceConfig. initialize</code></p>
<p><code>cloudaicompanion.companions.*</code></p>
<ul>
<li><code>cloudaicompanion. companions. generateChat</code></li>
<li><code>cloudaicompanion. companions. generateCode</code></li>
</ul>
<p><code>cloudaicompanion. entitlements. get</code></p>
<p><code>cloudaicompanion. instances. completeCode</code></p>
<p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>cloudaicompanion. instances. generateCode</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>cloudsql.*</code></p>
<ul>
<li><code>cloudsql.backupRuns.create</code></li>
<li><code>cloudsql.backupRuns.delete</code></li>
<li><code>cloudsql.backupRuns.export</code></li>
<li><code>cloudsql.backupRuns.get</code></li>
<li><code>cloudsql.backupRuns.list</code></li>
<li><code>cloudsql.backupRuns.update</code></li>
<li><code>cloudsql. blueGreenDeployments. create</code></li>
<li><code>cloudsql. blueGreenDeployments. delete</code></li>
<li><code>cloudsql. blueGreenDeployments. get</code></li>
<li><code>cloudsql. blueGreenDeployments. list</code></li>
<li><code>cloudsql. blueGreenDeployments. switchover</code></li>
<li><code>cloudsql.databases.create</code></li>
<li><code>cloudsql.databases.delete</code></li>
<li><code>cloudsql.databases.get</code></li>
<li><code>cloudsql.databases.list</code></li>
<li><code>cloudsql.databases.update</code></li>
<li><code>cloudsql. instances. addEntraIdCertificate</code></li>
<li><code>cloudsql.instances.addServerCa</code></li>
<li><code>cloudsql. instances. addServerCertificate</code></li>
<li><code>cloudsql. instances. cancelAgentSession</code></li>
<li><code>cloudsql.instances.clone</code></li>
<li><code>cloudsql.instances.connect</code></li>
<li><code>cloudsql.instances.create</code></li>
<li><code>cloudsql. instances. createBackupDrBackup</code></li>
<li><code>cloudsql. instances. createTagBinding</code></li>
<li><code>cloudsql. instances. createTestingAgentSession</code></li>
<li><code>cloudsql.instances.delete</code></li>
<li><code>cloudsql. instances. deleteTagBinding</code></li>
<li><code>cloudsql. instances. demoteMaster</code></li>
<li><code>cloudsql.instances.executeSql</code></li>
<li><code>cloudsql.instances.export</code></li>
<li><code>cloudsql.instances.failover</code></li>
<li><code>cloudsql.instances.get</code></li>
<li><code>cloudsql. instances. getAgentSession</code></li>
<li><code>cloudsql. instances. getDiskShrinkConfig</code></li>
<li><code>cloudsql.instances.import</code></li>
<li><code>cloudsql.instances.list</code></li>
<li><code>cloudsql. instances. listAgentSessions</code></li>
<li><code>cloudsql. instances. listEffectiveTags</code></li>
<li><code>cloudsql. instances. listEntraIdCertificates</code></li>
<li><code>cloudsql. instances. listServerCas</code></li>
<li><code>cloudsql. instances. listServerCertificates</code></li>
<li><code>cloudsql. instances. listTagBindings</code></li>
<li><code>cloudsql.instances.login</code></li>
<li><code>cloudsql. instances. manageEncryption</code></li>
<li><code>cloudsql.instances.migrate</code></li>
<li><code>cloudsql. instances. performDiskShrink</code></li>
<li><code>cloudsql. instances. preCheckMajorVersionUpgrade</code></li>
<li><code>cloudsql. instances. promoteReplica</code></li>
<li><code>cloudsql.instances.reencrypt</code></li>
<li><code>cloudsql. instances. resetReplicaSize</code></li>
<li><code>cloudsql. instances. resetSslConfig</code></li>
<li><code>cloudsql.instances.restart</code></li>
<li><code>cloudsql. instances. restoreBackup</code></li>
<li><code>cloudsql. instances. rotateEntraIdCertificate</code></li>
<li><code>cloudsql. instances. rotateServerCa</code></li>
<li><code>cloudsql. instances. rotateServerCertificate</code></li>
<li><code>cloudsql. instances. startReplica</code></li>
<li><code>cloudsql.instances.stopReplica</code></li>
<li><code>cloudsql.instances.truncateLog</code></li>
<li><code>cloudsql.instances.update</code></li>
<li><code>cloudsql. instances. updateBackupDrConfig</code></li>
<li><code>cloudsql.schemas.view</code></li>
<li><code>cloudsql.sslCerts.create</code></li>
<li><code>cloudsql.sslCerts.delete</code></li>
<li><code>cloudsql.sslCerts.get</code></li>
<li><code>cloudsql.sslCerts.list</code></li>
<li><code>cloudsql.users.create</code></li>
<li><code>cloudsql.users.delete</code></li>
<li><code>cloudsql.users.get</code></li>
<li><code>cloudsql.users.list</code></li>
<li><code>cloudsql.users.update</code></li>
<li><code>cloudsql.workloadCaptures.list</code></li>
<li><code>cloudsql. workloadCaptures. start</code></li>
<li><code>cloudsql. workloadCaptures. startReplay</code></li>
<li><code>cloudsql.workloadCaptures.stop</code></li>
<li><code>cloudsql. workloadCaptures. stopReplay</code></li>
</ul>
<p><code>composer.dags.get</code></p>
<p><code>composer.environments.get</code></p>
<p><code>compute.acceleratorTypes.*</code></p>
<ul>
<li><code>compute.acceleratorTypes.get</code></li>
<li><code>compute.acceleratorTypes.list</code></li>
</ul>
<p><code>compute.addresses.*</code></p>
<ul>
<li><code>compute.addresses.create</code></li>
<li><code>compute. addresses. createInternal</code></li>
<li><code>compute. addresses. createTagBinding</code></li>
<li><code>compute.addresses.delete</code></li>
<li><code>compute. addresses. deleteInternal</code></li>
<li><code>compute. addresses. deleteTagBinding</code></li>
<li><code>compute.addresses.get</code></li>
<li><code>compute.addresses.list</code></li>
<li><code>compute. addresses. listEffectiveTags</code></li>
<li><code>compute. addresses. listTagBindings</code></li>
<li><code>compute.addresses.setLabels</code></li>
<li><code>compute.addresses.use</code></li>
<li><code>compute.addresses.useInternal</code></li>
</ul>
<p><code>compute.autoscalers.*</code></p>
<ul>
<li><code>compute.autoscalers.create</code></li>
<li><code>compute.autoscalers.delete</code></li>
<li><code>compute.autoscalers.get</code></li>
<li><code>compute.autoscalers.list</code></li>
<li><code>compute.autoscalers.update</code></li>
</ul>
<p><code>compute.backendBuckets.*</code></p>
<ul>
<li><code>compute. backendBuckets. addSignedUrlKey</code></li>
<li><code>compute.backendBuckets.create</code></li>
<li><code>compute. backendBuckets. createTagBinding</code></li>
<li><code>compute.backendBuckets.delete</code></li>
<li><code>compute. backendBuckets. deleteSignedUrlKey</code></li>
<li><code>compute. backendBuckets. deleteTagBinding</code></li>
<li><code>compute.backendBuckets.get</code></li>
<li><code>compute. backendBuckets. getIamPolicy</code></li>
<li><code>compute.backendBuckets.list</code></li>
<li><code>compute. backendBuckets. listEffectiveTags</code></li>
<li><code>compute. backendBuckets. listTagBindings</code></li>
<li><code>compute. backendBuckets. setIamPolicy</code></li>
<li><code>compute. backendBuckets. setSecurityPolicy</code></li>
<li><code>compute.backendBuckets.update</code></li>
<li><code>compute.backendBuckets.use</code></li>
</ul>
<p><code>compute.backendServices.*</code></p>
<ul>
<li><code>compute. backendServices. addSignedUrlKey</code></li>
<li><code>compute.backendServices.create</code></li>
<li><code>compute. backendServices. createTagBinding</code></li>
<li><code>compute.backendServices.delete</code></li>
<li><code>compute. backendServices. deleteSignedUrlKey</code></li>
<li><code>compute. backendServices. deleteTagBinding</code></li>
<li><code>compute.backendServices.get</code></li>
<li><code>compute. backendServices. getIamPolicy</code></li>
<li><code>compute.backendServices.list</code></li>
<li><code>compute. backendServices. listEffectiveTags</code></li>
<li><code>compute. backendServices. listTagBindings</code></li>
<li><code>compute. backendServices. setIamPolicy</code></li>
<li><code>compute. backendServices. setSecurityPolicy</code></li>
<li><code>compute.backendServices.update</code></li>
<li><code>compute.backendServices.use</code></li>
</ul>
<p><code>compute.crossSiteNetworks.*</code></p>
<ul>
<li><code>compute. crossSiteNetworks. create</code></li>
<li><code>compute. crossSiteNetworks. delete</code></li>
<li><code>compute.crossSiteNetworks.get</code></li>
<li><code>compute.crossSiteNetworks.list</code></li>
<li><code>compute. crossSiteNetworks. update</code></li>
</ul>
<p><code>compute.diskSettings.get</code></p>
<p><code>compute.diskTypes.*</code></p>
<ul>
<li><code>compute.diskTypes.get</code></li>
<li><code>compute.diskTypes.list</code></li>
</ul>
<p><code>compute.disks.*</code></p>
<ul>
<li><code>compute. disks. addResourcePolicies</code></li>
<li><code>compute.disks.create</code></li>
<li><code>compute.disks.createSnapshot</code></li>
<li><code>compute.disks.createTagBinding</code></li>
<li><code>compute.disks.delete</code></li>
<li><code>compute.disks.deleteTagBinding</code></li>
<li><code>compute.disks.get</code></li>
<li><code>compute.disks.getIamPolicy</code></li>
<li><code>compute.disks.list</code></li>
<li><code>compute. disks. listEffectiveTags</code></li>
<li><code>compute.disks.listTagBindings</code></li>
<li><code>compute. disks. removeResourcePolicies</code></li>
<li><code>compute.disks.resize</code></li>
<li><code>compute.disks.setIamPolicy</code></li>
<li><code>compute.disks.setLabels</code></li>
<li><code>compute. disks. startAsyncReplication</code></li>
<li><code>compute. disks. stopAsyncReplication</code></li>
<li><code>compute. disks. stopGroupAsyncReplication</code></li>
<li><code>compute.disks.update</code></li>
<li><code>compute.disks.updateKmsKey</code></li>
<li><code>compute.disks.use</code></li>
<li><code>compute.disks.useReadOnly</code></li>
</ul>
<p><code>compute.externalVpnGateways.*</code></p>
<ul>
<li><code>compute. externalVpnGateways. create</code></li>
<li><code>compute. externalVpnGateways. createTagBinding</code></li>
<li><code>compute. externalVpnGateways. delete</code></li>
<li><code>compute. externalVpnGateways. deleteTagBinding</code></li>
<li><code>compute. externalVpnGateways. get</code></li>
<li><code>compute. externalVpnGateways. list</code></li>
<li><code>compute. externalVpnGateways. listEffectiveTags</code></li>
<li><code>compute. externalVpnGateways. listTagBindings</code></li>
<li><code>compute. externalVpnGateways. setLabels</code></li>
<li><code>compute. externalVpnGateways. use</code></li>
</ul>
<p><code>compute.firewallPolicies.get</code></p>
<p><code>compute.firewallPolicies.list</code></p>
<p><code>compute. firewallPolicies. listEffectiveTags</code></p>
<p><code>compute. firewallPolicies. listTagBindings</code></p>
<p><code>compute.firewallPolicies.use</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute. firewalls. listEffectiveTags</code></p>
<p><code>compute. firewalls. listTagBindings</code></p>
<p><code>compute.forwardingRules.*</code></p>
<ul>
<li><code>compute.forwardingRules.create</code></li>
<li><code>compute. forwardingRules. createTagBinding</code></li>
<li><code>compute.forwardingRules.delete</code></li>
<li><code>compute. forwardingRules. deleteTagBinding</code></li>
<li><code>compute.forwardingRules.get</code></li>
<li><code>compute.forwardingRules.list</code></li>
<li><code>compute. forwardingRules. listEffectiveTags</code></li>
<li><code>compute. forwardingRules. listTagBindings</code></li>
<li><code>compute. forwardingRules. pscCreate</code></li>
<li><code>compute. forwardingRules. pscDelete</code></li>
<li><code>compute. forwardingRules. pscSetLabels</code></li>
<li><code>compute. forwardingRules. pscUpdate</code></li>
<li><code>compute. forwardingRules. setLabels</code></li>
<li><code>compute. forwardingRules. setTarget</code></li>
<li><code>compute.forwardingRules.update</code></li>
<li><code>compute.forwardingRules.use</code></li>
</ul>
<p><code>compute.globalAddresses.*</code></p>
<ul>
<li><code>compute.globalAddresses.create</code></li>
<li><code>compute. globalAddresses. createInternal</code></li>
<li><code>compute. globalAddresses. createTagBinding</code></li>
<li><code>compute.globalAddresses.delete</code></li>
<li><code>compute. globalAddresses. deleteInternal</code></li>
<li><code>compute. globalAddresses. deleteTagBinding</code></li>
<li><code>compute.globalAddresses.get</code></li>
<li><code>compute.globalAddresses.list</code></li>
<li><code>compute. globalAddresses. listEffectiveTags</code></li>
<li><code>compute. globalAddresses. listTagBindings</code></li>
<li><code>compute. globalAddresses. setLabels</code></li>
<li><code>compute.globalAddresses.use</code></li>
</ul>
<p><code>compute. globalForwardingRules.*</code></p>
<ul>
<li><code>compute. globalForwardingRules. create</code></li>
<li><code>compute. globalForwardingRules. createTagBinding</code></li>
<li><code>compute. globalForwardingRules. delete</code></li>
<li><code>compute. globalForwardingRules. deleteTagBinding</code></li>
<li><code>compute. globalForwardingRules. get</code></li>
<li><code>compute. globalForwardingRules. list</code></li>
<li><code>compute. globalForwardingRules. listEffectiveTags</code></li>
<li><code>compute. globalForwardingRules. listTagBindings</code></li>
<li><code>compute. globalForwardingRules. pscCreate</code></li>
<li><code>compute. globalForwardingRules. pscDelete</code></li>
<li><code>compute. globalForwardingRules. pscSetLabels</code></li>
<li><code>compute. globalForwardingRules. pscUpdate</code></li>
<li><code>compute. globalForwardingRules. setLabels</code></li>
<li><code>compute. globalForwardingRules. setTarget</code></li>
<li><code>compute. globalForwardingRules. update</code></li>
</ul>
<p><code>compute. globalFrontendSettings.*</code></p>
<ul>
<li><code>compute. globalFrontendSettings. get</code></li>
<li><code>compute. globalFrontendSettings. update</code></li>
</ul>
<p><code>compute. globalNetworkEndpointGroups.*</code></p>
<ul>
<li><code>compute. globalNetworkEndpointGroups. attachNetworkEndpoints</code></li>
<li><code>compute. globalNetworkEndpointGroups. create</code></li>
<li><code>compute. globalNetworkEndpointGroups. createTagBinding</code></li>
<li><code>compute. globalNetworkEndpointGroups. delete</code></li>
<li><code>compute. globalNetworkEndpointGroups. deleteTagBinding</code></li>
<li><code>compute. globalNetworkEndpointGroups. detachNetworkEndpoints</code></li>
<li><code>compute. globalNetworkEndpointGroups. get</code></li>
<li><code>compute. globalNetworkEndpointGroups. list</code></li>
<li><code>compute. globalNetworkEndpointGroups. listEffectiveTags</code></li>
<li><code>compute. globalNetworkEndpointGroups. listTagBindings</code></li>
<li><code>compute. globalNetworkEndpointGroups. use</code></li>
</ul>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.globalOperations.list</code></p>
<p><code>compute. globalPublicDelegatedPrefixes. delete</code></p>
<p><code>compute. globalPublicDelegatedPrefixes. get</code></p>
<p><code>compute. globalPublicDelegatedPrefixes. list</code></p>
<p><code>compute. globalPublicDelegatedPrefixes. updatePolicy</code></p>
<p><code>compute.healthChecks.*</code></p>
<ul>
<li><code>compute.healthChecks.create</code></li>
<li><code>compute. healthChecks. createTagBinding</code></li>
<li><code>compute.healthChecks.delete</code></li>
<li><code>compute. healthChecks. deleteTagBinding</code></li>
<li><code>compute.healthChecks.get</code></li>
<li><code>compute.healthChecks.list</code></li>
<li><code>compute. healthChecks. listEffectiveTags</code></li>
<li><code>compute. healthChecks. listTagBindings</code></li>
<li><code>compute.healthChecks.update</code></li>
<li><code>compute.healthChecks.use</code></li>
<li><code>compute. healthChecks. useReadOnly</code></li>
</ul>
<p><code>compute.hosts.*</code></p>
<ul>
<li><code>compute.hosts.get</code></li>
<li><code>compute.hosts.getVersion</code></li>
<li><code>compute.hosts.list</code></li>
</ul>
<p><code>compute.httpHealthChecks.*</code></p>
<ul>
<li><code>compute. httpHealthChecks. create</code></li>
<li><code>compute. httpHealthChecks. createTagBinding</code></li>
<li><code>compute. httpHealthChecks. delete</code></li>
<li><code>compute. httpHealthChecks. deleteTagBinding</code></li>
<li><code>compute.httpHealthChecks.get</code></li>
<li><code>compute.httpHealthChecks.list</code></li>
<li><code>compute. httpHealthChecks. listEffectiveTags</code></li>
<li><code>compute. httpHealthChecks. listTagBindings</code></li>
<li><code>compute. httpHealthChecks. update</code></li>
<li><code>compute.httpHealthChecks.use</code></li>
<li><code>compute. httpHealthChecks. useReadOnly</code></li>
</ul>
<p><code>compute.httpsHealthChecks.*</code></p>
<ul>
<li><code>compute. httpsHealthChecks. create</code></li>
<li><code>compute. httpsHealthChecks. createTagBinding</code></li>
<li><code>compute. httpsHealthChecks. delete</code></li>
<li><code>compute. httpsHealthChecks. deleteTagBinding</code></li>
<li><code>compute.httpsHealthChecks.get</code></li>
<li><code>compute.httpsHealthChecks.list</code></li>
<li><code>compute. httpsHealthChecks. listEffectiveTags</code></li>
<li><code>compute. httpsHealthChecks. listTagBindings</code></li>
<li><code>compute. httpsHealthChecks. update</code></li>
<li><code>compute.httpsHealthChecks.use</code></li>
<li><code>compute. httpsHealthChecks. useReadOnly</code></li>
</ul>
<p><code>compute.images.*</code></p>
<ul>
<li><code>compute.images.create</code></li>
<li><code>compute. images. createTagBinding</code></li>
<li><code>compute.images.delete</code></li>
<li><code>compute. images. deleteTagBinding</code></li>
<li><code>compute.images.deprecate</code></li>
<li><code>compute.images.get</code></li>
<li><code>compute.images.getFromFamily</code></li>
<li><code>compute.images.getIamPolicy</code></li>
<li><code>compute.images.list</code></li>
<li><code>compute. images. listEffectiveTags</code></li>
<li><code>compute.images.listTagBindings</code></li>
<li><code>compute.images.setIamPolicy</code></li>
<li><code>compute.images.setLabels</code></li>
<li><code>compute.images.update</code></li>
<li><code>compute.images.useReadOnly</code></li>
</ul>
<p><code>compute. instanceGroupManagers.*</code></p>
<ul>
<li><code>compute. instanceGroupManagers. create</code></li>
<li><code>compute. instanceGroupManagers. createTagBinding</code></li>
<li><code>compute. instanceGroupManagers. delete</code></li>
<li><code>compute. instanceGroupManagers. deleteTagBinding</code></li>
<li><code>compute. instanceGroupManagers. get</code></li>
<li><code>compute. instanceGroupManagers. list</code></li>
<li><code>compute. instanceGroupManagers. listEffectiveTags</code></li>
<li><code>compute. instanceGroupManagers. listTagBindings</code></li>
<li><code>compute. instanceGroupManagers. update</code></li>
<li><code>compute. instanceGroupManagers. use</code></li>
</ul>
<p><code>compute.instanceGroups.*</code></p>
<ul>
<li><code>compute.instanceGroups.create</code></li>
<li><code>compute. instanceGroups. createTagBinding</code></li>
<li><code>compute.instanceGroups.delete</code></li>
<li><code>compute. instanceGroups. deleteTagBinding</code></li>
<li><code>compute.instanceGroups.get</code></li>
<li><code>compute.instanceGroups.list</code></li>
<li><code>compute. instanceGroups. listEffectiveTags</code></li>
<li><code>compute. instanceGroups. listTagBindings</code></li>
<li><code>compute.instanceGroups.update</code></li>
<li><code>compute.instanceGroups.use</code></li>
</ul>
<p><code>compute.instanceSettings.*</code></p>
<ul>
<li><code>compute.instanceSettings.get</code></li>
<li><code>compute. instanceSettings. update</code></li>
</ul>
<p><code>compute.instanceTemplates.*</code></p>
<ul>
<li><code>compute. instanceTemplates. create</code></li>
<li><code>compute. instanceTemplates. delete</code></li>
<li><code>compute.instanceTemplates.get</code></li>
<li><code>compute. instanceTemplates. getIamPolicy</code></li>
<li><code>compute.instanceTemplates.list</code></li>
<li><code>compute. instanceTemplates. setIamPolicy</code></li>
<li><code>compute. instanceTemplates. useReadOnly</code></li>
</ul>
<p><code>compute.instances.*</code></p>
<ul>
<li><code>compute. instances. addAccessConfig</code></li>
<li><code>compute. instances. addNetworkInterface</code></li>
<li><code>compute. instances. addResourcePolicies</code></li>
<li><code>compute.instances.attachDisk</code></li>
<li><code>compute.instances.create</code></li>
<li><code>compute. instances. createTagBinding</code></li>
<li><code>compute.instances.delete</code></li>
<li><code>compute. instances. deleteAccessConfig</code></li>
<li><code>compute. instances. deleteNetworkInterface</code></li>
<li><code>compute. instances. deleteTagBinding</code></li>
<li><code>compute.instances.detachDisk</code></li>
<li><code>compute.instances.get</code></li>
<li><code>compute. instances. getEffectiveFirewalls</code></li>
<li><code>compute. instances. getGuestAttributes</code></li>
<li><code>compute.instances.getIamPolicy</code></li>
<li><code>compute. instances. getScreenshot</code></li>
<li><code>compute. instances. getSerialPortOutput</code></li>
<li><code>compute. instances. getShieldedInstanceIdentity</code></li>
<li><code>compute. instances. getShieldedVmIdentity</code></li>
<li><code>compute. instances. getVmExtensionState</code></li>
<li><code>compute.instances.list</code></li>
<li><code>compute. instances. listEffectiveTags</code></li>
<li><code>compute. instances. listReferrers</code></li>
<li><code>compute. instances. listTagBindings</code></li>
<li><code>compute. instances. listVmExtensionStates</code></li>
<li><code>compute.instances.osAdminLogin</code></li>
<li><code>compute.instances.osLogin</code></li>
<li><code>compute. instances. performMaintenance</code></li>
<li><code>compute. instances. pscInterfaceCreate</code></li>
<li><code>compute. instances. removeResourcePolicies</code></li>
<li><code>compute.instances.reset</code></li>
<li><code>compute.instances.resume</code></li>
<li><code>compute. instances. sendDiagnosticInterrupt</code></li>
<li><code>compute. instances. setDeletionProtection</code></li>
<li><code>compute. instances. setDiskAutoDelete</code></li>
<li><code>compute.instances.setIamPolicy</code></li>
<li><code>compute.instances.setLabels</code></li>
<li><code>compute. instances. setMachineResources</code></li>
<li><code>compute. instances. setMachineType</code></li>
<li><code>compute.instances.setMetadata</code></li>
<li><code>compute. instances. setMinCpuPlatform</code></li>
<li><code>compute.instances.setName</code></li>
<li><code>compute. instances. setScheduling</code></li>
<li><code>compute. instances. setSecurityPolicy</code></li>
<li><code>compute. instances. setServiceAccount</code></li>
<li><code>compute. instances. setShieldedInstanceIntegrityPolicy</code></li>
<li><code>compute. instances. setShieldedVmIntegrityPolicy</code></li>
<li><code>compute.instances.setTags</code></li>
<li><code>compute. instances. simulateMaintenanceEvent</code></li>
<li><code>compute.instances.start</code></li>
<li><code>compute. instances. startWithEncryptionKey</code></li>
<li><code>compute.instances.stop</code></li>
<li><code>compute.instances.suspend</code></li>
<li><code>compute.instances.troubleshoot</code></li>
<li><code>compute.instances.update</code></li>
<li><code>compute. instances. updateAccessConfig</code></li>
<li><code>compute. instances. updateDisplayDevice</code></li>
<li><code>compute. instances. updateNetworkInterface</code></li>
<li><code>compute. instances. updateSecurity</code></li>
<li><code>compute. instances. updateShieldedInstanceConfig</code></li>
<li><code>compute. instances. updateShieldedVmConfig</code></li>
<li><code>compute.instances.use</code></li>
<li><code>compute.instances.useReadOnly</code></li>
</ul>
<p><code>compute. instantSnapshotGroups.*</code></p>
<ul>
<li><code>compute. instantSnapshotGroups. create</code></li>
<li><code>compute. instantSnapshotGroups. delete</code></li>
<li><code>compute. instantSnapshotGroups. get</code></li>
<li><code>compute. instantSnapshotGroups. getIamPolicy</code></li>
<li><code>compute. instantSnapshotGroups. list</code></li>
<li><code>compute. instantSnapshotGroups. setIamPolicy</code></li>
<li><code>compute. instantSnapshotGroups. useReadOnly</code></li>
</ul>
<p><code>compute. instantSnapshots. create</code></p>
<p><code>compute. instantSnapshots. delete</code></p>
<p><code>compute. instantSnapshots. export</code></p>
<p><code>compute.instantSnapshots.get</code></p>
<p><code>compute. instantSnapshots. getIamPolicy</code></p>
<p><code>compute.instantSnapshots.list</code></p>
<p><code>compute. instantSnapshots. listEffectiveTags</code></p>
<p><code>compute. instantSnapshots. listTagBindings</code></p>
<p><code>compute. instantSnapshots. setIamPolicy</code></p>
<p><code>compute. instantSnapshots. setLabels</code></p>
<p><code>compute. instantSnapshots. useReadOnly</code></p>
<p><code>compute. interconnectAttachmentGroups.*</code></p>
<ul>
<li><code>compute. interconnectAttachmentGroups. create</code></li>
<li><code>compute. interconnectAttachmentGroups. delete</code></li>
<li><code>compute. interconnectAttachmentGroups. get</code></li>
<li><code>compute. interconnectAttachmentGroups. list</code></li>
<li><code>compute. interconnectAttachmentGroups. patch</code></li>
</ul>
<p><code>compute. interconnectAttachments.*</code></p>
<ul>
<li><code>compute. interconnectAttachments. create</code></li>
<li><code>compute. interconnectAttachments. createTagBinding</code></li>
<li><code>compute. interconnectAttachments. delete</code></li>
<li><code>compute. interconnectAttachments. deleteTagBinding</code></li>
<li><code>compute. interconnectAttachments. get</code></li>
<li><code>compute. interconnectAttachments. list</code></li>
<li><code>compute. interconnectAttachments. listEffectiveTags</code></li>
<li><code>compute. interconnectAttachments. listTagBindings</code></li>
<li><code>compute. interconnectAttachments. setLabels</code></li>
<li><code>compute. interconnectAttachments. update</code></li>
<li><code>compute. interconnectAttachments. use</code></li>
</ul>
<p><code>compute.interconnectGroups.*</code></p>
<ul>
<li><code>compute. interconnectGroups. create</code></li>
<li><code>compute. interconnectGroups. delete</code></li>
<li><code>compute.interconnectGroups.get</code></li>
<li><code>compute. interconnectGroups. list</code></li>
<li><code>compute. interconnectGroups. patch</code></li>
</ul>
<p><code>compute. interconnectLocations.*</code></p>
<ul>
<li><code>compute. interconnectLocations. get</code></li>
<li><code>compute. interconnectLocations. list</code></li>
</ul>
<p><code>compute. interconnectRemoteLocations.*</code></p>
<ul>
<li><code>compute. interconnectRemoteLocations. get</code></li>
<li><code>compute. interconnectRemoteLocations. list</code></li>
</ul>
<p><code>compute.interconnects.*</code></p>
<ul>
<li><code>compute.interconnects.create</code></li>
<li><code>compute. interconnects. createTagBinding</code></li>
<li><code>compute.interconnects.delete</code></li>
<li><code>compute. interconnects. deleteTagBinding</code></li>
<li><code>compute.interconnects.get</code></li>
<li><code>compute. interconnects. getMacsecConfig</code></li>
<li><code>compute.interconnects.list</code></li>
<li><code>compute. interconnects. listEffectiveTags</code></li>
<li><code>compute. interconnects. listTagBindings</code></li>
<li><code>compute. interconnects. setLabels</code></li>
<li><code>compute.interconnects.setName</code></li>
<li><code>compute.interconnects.update</code></li>
<li><code>compute.interconnects.use</code></li>
</ul>
<p><code>compute.licenseCodes.*</code></p>
<ul>
<li><code>compute.licenseCodes.get</code></li>
<li><code>compute. licenseCodes. getIamPolicy</code></li>
<li><code>compute.licenseCodes.list</code></li>
<li><code>compute. licenseCodes. setIamPolicy</code></li>
</ul>
<p><code>compute.licenses.create</code></p>
<p><code>compute.licenses.delete</code></p>
<p><code>compute.licenses.get</code></p>
<p><code>compute.licenses.getIamPolicy</code></p>
<p><code>compute.licenses.list</code></p>
<p><code>compute. licenses. listEffectiveTags</code></p>
<p><code>compute. licenses. listTagBindings</code></p>
<p><code>compute.licenses.setIamPolicy</code></p>
<p><code>compute.licenses.update</code></p>
<p><code>compute.machineImages.create</code></p>
<p><code>compute.machineImages.delete</code></p>
<p><code>compute.machineImages.get</code></p>
<p><code>compute. machineImages. getIamPolicy</code></p>
<p><code>compute.machineImages.list</code></p>
<p><code>compute. machineImages. listEffectiveTags</code></p>
<p><code>compute. machineImages. listTagBindings</code></p>
<p><code>compute. machineImages. setIamPolicy</code></p>
<p><code>compute. machineImages. setLabels</code></p>
<p><code>compute. machineImages. useReadOnly</code></p>
<p><code>compute.machineTypes.*</code></p>
<ul>
<li><code>compute.machineTypes.get</code></li>
<li><code>compute.machineTypes.list</code></li>
</ul>
<p><code>compute.multiMig.*</code></p>
<ul>
<li><code>compute.multiMig.create</code></li>
<li><code>compute.multiMig.delete</code></li>
<li><code>compute.multiMig.get</code></li>
<li><code>compute.multiMig.list</code></li>
</ul>
<p><code>compute.multiMigMembers.*</code></p>
<ul>
<li><code>compute.multiMigMembers.get</code></li>
<li><code>compute.multiMigMembers.list</code></li>
</ul>
<p><code>compute.networkAttachments.*</code></p>
<ul>
<li><code>compute. networkAttachments. create</code></li>
<li><code>compute. networkAttachments. createTagBinding</code></li>
<li><code>compute. networkAttachments. delete</code></li>
<li><code>compute. networkAttachments. deleteTagBinding</code></li>
<li><code>compute.networkAttachments.get</code></li>
<li><code>compute. networkAttachments. getIamPolicy</code></li>
<li><code>compute. networkAttachments. list</code></li>
<li><code>compute. networkAttachments. listEffectiveTags</code></li>
<li><code>compute. networkAttachments. listTagBindings</code></li>
<li><code>compute. networkAttachments. setIamPolicy</code></li>
<li><code>compute. networkAttachments. update</code></li>
<li><code>compute.networkAttachments.use</code></li>
</ul>
<p><code>compute. networkEndpointGroups.*</code></p>
<ul>
<li><code>compute. networkEndpointGroups. attachNetworkEndpoints</code></li>
<li><code>compute. networkEndpointGroups. create</code></li>
<li><code>compute. networkEndpointGroups. createTagBinding</code></li>
<li><code>compute. networkEndpointGroups. delete</code></li>
<li><code>compute. networkEndpointGroups. deleteTagBinding</code></li>
<li><code>compute. networkEndpointGroups. detachNetworkEndpoints</code></li>
<li><code>compute. networkEndpointGroups. get</code></li>
<li><code>compute. networkEndpointGroups. list</code></li>
<li><code>compute. networkEndpointGroups. listEffectiveTags</code></li>
<li><code>compute. networkEndpointGroups. listTagBindings</code></li>
<li><code>compute. networkEndpointGroups. use</code></li>
</ul>
<p><code>compute.networkProfiles.*</code></p>
<ul>
<li><code>compute.networkProfiles.get</code></li>
<li><code>compute.networkProfiles.list</code></li>
</ul>
<p><code>compute.networks.*</code></p>
<ul>
<li><code>compute.networks.access</code></li>
<li><code>compute.networks.addPeering</code></li>
<li><code>compute.networks.create</code></li>
<li><code>compute. networks. createTagBinding</code></li>
<li><code>compute.networks.delete</code></li>
<li><code>compute. networks. deleteTagBinding</code></li>
<li><code>compute.networks.get</code></li>
<li><code>compute. networks. getEffectiveFirewalls</code></li>
<li><code>compute. networks. getRegionEffectiveFirewalls</code></li>
<li><code>compute.networks.list</code></li>
<li><code>compute. networks. listEffectiveTags</code></li>
<li><code>compute. networks. listPeeringRoutes</code></li>
<li><code>compute. networks. listTagBindings</code></li>
<li><code>compute.networks.mirror</code></li>
<li><code>compute.networks.removePeering</code></li>
<li><code>compute. networks. setFirewallPolicy</code></li>
<li><code>compute. networks. setNetworkPolicy</code></li>
<li><code>compute. networks. switchToCustomMode</code></li>
<li><code>compute.networks.update</code></li>
<li><code>compute.networks.updatePeering</code></li>
<li><code>compute.networks.updatePolicy</code></li>
<li><code>compute.networks.use</code></li>
<li><code>compute.networks.useExternalIp</code></li>
</ul>
<p><code>compute.packetMirrorings.get</code></p>
<p><code>compute.packetMirrorings.list</code></p>
<p><code>compute. packetMirrorings. listEffectiveTags</code></p>
<p><code>compute. packetMirrorings. listTagBindings</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. projects. setCommonInstanceMetadata</code></p>
<p><code>compute. publicDelegatedPrefixes. delete</code></p>
<p><code>compute. publicDelegatedPrefixes. get</code></p>
<p><code>compute. publicDelegatedPrefixes. list</code></p>
<p><code>compute. publicDelegatedPrefixes. listEffectiveTags</code></p>
<p><code>compute. publicDelegatedPrefixes. listTagBindings</code></p>
<p><code>compute. publicDelegatedPrefixes. update</code></p>
<p><code>compute. publicDelegatedPrefixes. updatePolicy</code></p>
<p><code>compute.recoverableSnapshots.*</code></p>
<ul>
<li><code>compute. recoverableSnapshots. delete</code></li>
<li><code>compute. recoverableSnapshots. get</code></li>
<li><code>compute. recoverableSnapshots. getIamPolicy</code></li>
<li><code>compute. recoverableSnapshots. list</code></li>
<li><code>compute. recoverableSnapshots. recover</code></li>
<li><code>compute. recoverableSnapshots. setIamPolicy</code></li>
</ul>
<p><code>compute.regionBackendBuckets.*</code></p>
<ul>
<li><code>compute. regionBackendBuckets. create</code></li>
<li><code>compute. regionBackendBuckets. createTagBinding</code></li>
<li><code>compute. regionBackendBuckets. delete</code></li>
<li><code>compute. regionBackendBuckets. deleteTagBinding</code></li>
<li><code>compute. regionBackendBuckets. get</code></li>
<li><code>compute. regionBackendBuckets. getIamPolicy</code></li>
<li><code>compute. regionBackendBuckets. list</code></li>
<li><code>compute. regionBackendBuckets. listEffectiveTags</code></li>
<li><code>compute. regionBackendBuckets. listTagBindings</code></li>
<li><code>compute. regionBackendBuckets. setIamPolicy</code></li>
<li><code>compute. regionBackendBuckets. update</code></li>
<li><code>compute. regionBackendBuckets. use</code></li>
</ul>
<p><code>compute. regionBackendServices.*</code></p>
<ul>
<li><code>compute. regionBackendServices. create</code></li>
<li><code>compute. regionBackendServices. createTagBinding</code></li>
<li><code>compute. regionBackendServices. delete</code></li>
<li><code>compute. regionBackendServices. deleteTagBinding</code></li>
<li><code>compute. regionBackendServices. get</code></li>
<li><code>compute. regionBackendServices. getIamPolicy</code></li>
<li><code>compute. regionBackendServices. list</code></li>
<li><code>compute. regionBackendServices. listEffectiveTags</code></li>
<li><code>compute. regionBackendServices. listTagBindings</code></li>
<li><code>compute. regionBackendServices. setIamPolicy</code></li>
<li><code>compute. regionBackendServices. setSecurityPolicy</code></li>
<li><code>compute. regionBackendServices. update</code></li>
<li><code>compute. regionBackendServices. use</code></li>
</ul>
<p><code>compute. regionCompositeHealthChecks.*</code></p>
<ul>
<li><code>compute. regionCompositeHealthChecks. create</code></li>
<li><code>compute. regionCompositeHealthChecks. delete</code></li>
<li><code>compute. regionCompositeHealthChecks. get</code></li>
<li><code>compute. regionCompositeHealthChecks. list</code></li>
<li><code>compute. regionCompositeHealthChecks. update</code></li>
</ul>
<p><code>compute. regionFirewallPolicies. get</code></p>
<p><code>compute. regionFirewallPolicies. list</code></p>
<p><code>compute. regionFirewallPolicies. listEffectiveTags</code></p>
<p><code>compute. regionFirewallPolicies. listTagBindings</code></p>
<p><code>compute. regionFirewallPolicies. use</code></p>
<p><code>compute. regionHealthAggregationPolicies.*</code></p>
<ul>
<li><code>compute. regionHealthAggregationPolicies. create</code></li>
<li><code>compute. regionHealthAggregationPolicies. delete</code></li>
<li><code>compute. regionHealthAggregationPolicies. get</code></li>
<li><code>compute. regionHealthAggregationPolicies. list</code></li>
<li><code>compute. regionHealthAggregationPolicies. update</code></li>
</ul>
<p><code>compute. regionHealthCheckServices.*</code></p>
<ul>
<li><code>compute. regionHealthCheckServices. create</code></li>
<li><code>compute. regionHealthCheckServices. delete</code></li>
<li><code>compute. regionHealthCheckServices. get</code></li>
<li><code>compute. regionHealthCheckServices. list</code></li>
<li><code>compute. regionHealthCheckServices. update</code></li>
<li><code>compute. regionHealthCheckServices. use</code></li>
</ul>
<p><code>compute.regionHealthChecks.*</code></p>
<ul>
<li><code>compute. regionHealthChecks. create</code></li>
<li><code>compute. regionHealthChecks. createTagBinding</code></li>
<li><code>compute. regionHealthChecks. delete</code></li>
<li><code>compute. regionHealthChecks. deleteTagBinding</code></li>
<li><code>compute.regionHealthChecks.get</code></li>
<li><code>compute. regionHealthChecks. list</code></li>
<li><code>compute. regionHealthChecks. listEffectiveTags</code></li>
<li><code>compute. regionHealthChecks. listTagBindings</code></li>
<li><code>compute. regionHealthChecks. update</code></li>
<li><code>compute.regionHealthChecks.use</code></li>
<li><code>compute. regionHealthChecks. useReadOnly</code></li>
</ul>
<p><code>compute.regionHealthSources.*</code></p>
<ul>
<li><code>compute. regionHealthSources. create</code></li>
<li><code>compute. regionHealthSources. delete</code></li>
<li><code>compute. regionHealthSources. get</code></li>
<li><code>compute. regionHealthSources. list</code></li>
<li><code>compute. regionHealthSources. update</code></li>
</ul>
<p><code>compute. regionNetworkEndpointGroups.*</code></p>
<ul>
<li><code>compute. regionNetworkEndpointGroups. attachNetworkEndpoints</code></li>
<li><code>compute. regionNetworkEndpointGroups. create</code></li>
<li><code>compute. regionNetworkEndpointGroups. createTagBinding</code></li>
<li><code>compute. regionNetworkEndpointGroups. delete</code></li>
<li><code>compute. regionNetworkEndpointGroups. deleteTagBinding</code></li>
<li><code>compute. regionNetworkEndpointGroups. detachNetworkEndpoints</code></li>
<li><code>compute. regionNetworkEndpointGroups. get</code></li>
<li><code>compute. regionNetworkEndpointGroups. list</code></li>
<li><code>compute. regionNetworkEndpointGroups. listEffectiveTags</code></li>
<li><code>compute. regionNetworkEndpointGroups. listTagBindings</code></li>
<li><code>compute. regionNetworkEndpointGroups. use</code></li>
</ul>
<p><code>compute. regionNetworkPolicies.*</code></p>
<ul>
<li><code>compute. regionNetworkPolicies. create</code></li>
<li><code>compute. regionNetworkPolicies. delete</code></li>
<li><code>compute. regionNetworkPolicies. get</code></li>
<li><code>compute. regionNetworkPolicies. list</code></li>
<li><code>compute. regionNetworkPolicies. update</code></li>
<li><code>compute. regionNetworkPolicies. use</code></li>
</ul>
<p><code>compute. regionNotificationEndpoints.*</code></p>
<ul>
<li><code>compute. regionNotificationEndpoints. create</code></li>
<li><code>compute. regionNotificationEndpoints. delete</code></li>
<li><code>compute. regionNotificationEndpoints. get</code></li>
<li><code>compute. regionNotificationEndpoints. list</code></li>
<li><code>compute. regionNotificationEndpoints. update</code></li>
<li><code>compute. regionNotificationEndpoints. use</code></li>
</ul>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.regionOperations.list</code></p>
<p><code>compute. regionSecurityPolicies. get</code></p>
<p><code>compute. regionSecurityPolicies. list</code></p>
<p><code>compute. regionSecurityPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSecurityPolicies. listTagBindings</code></p>
<p><code>compute. regionSecurityPolicies. use</code></p>
<p><code>compute. regionSslCertificates. get</code></p>
<p><code>compute. regionSslCertificates. list</code></p>
<p><code>compute. regionSslCertificates. listEffectiveTags</code></p>
<p><code>compute. regionSslCertificates. listTagBindings</code></p>
<p><code>compute.regionSslPolicies.*</code></p>
<ul>
<li><code>compute. regionSslPolicies. create</code></li>
<li><code>compute. regionSslPolicies. createTagBinding</code></li>
<li><code>compute. regionSslPolicies. delete</code></li>
<li><code>compute. regionSslPolicies. deleteTagBinding</code></li>
<li><code>compute.regionSslPolicies.get</code></li>
<li><code>compute. regionSslPolicies. getIamPolicy</code></li>
<li><code>compute.regionSslPolicies.list</code></li>
<li><code>compute. regionSslPolicies. listAvailableFeatures</code></li>
<li><code>compute. regionSslPolicies. listEffectiveTags</code></li>
<li><code>compute. regionSslPolicies. listTagBindings</code></li>
<li><code>compute. regionSslPolicies. setIamPolicy</code></li>
<li><code>compute. regionSslPolicies. update</code></li>
<li><code>compute.regionSslPolicies.use</code></li>
</ul>
<p><code>compute. regionTargetHttpProxies.*</code></p>
<ul>
<li><code>compute. regionTargetHttpProxies. create</code></li>
<li><code>compute. regionTargetHttpProxies. createTagBinding</code></li>
<li><code>compute. regionTargetHttpProxies. delete</code></li>
<li><code>compute. regionTargetHttpProxies. deleteTagBinding</code></li>
<li><code>compute. regionTargetHttpProxies. get</code></li>
<li><code>compute. regionTargetHttpProxies. list</code></li>
<li><code>compute. regionTargetHttpProxies. listEffectiveTags</code></li>
<li><code>compute. regionTargetHttpProxies. listTagBindings</code></li>
<li><code>compute. regionTargetHttpProxies. setUrlMap</code></li>
<li><code>compute. regionTargetHttpProxies. use</code></li>
</ul>
<p><code>compute. regionTargetHttpsProxies.*</code></p>
<ul>
<li><code>compute. regionTargetHttpsProxies. create</code></li>
<li><code>compute. regionTargetHttpsProxies. createTagBinding</code></li>
<li><code>compute. regionTargetHttpsProxies. delete</code></li>
<li><code>compute. regionTargetHttpsProxies. deleteTagBinding</code></li>
<li><code>compute. regionTargetHttpsProxies. get</code></li>
<li><code>compute. regionTargetHttpsProxies. list</code></li>
<li><code>compute. regionTargetHttpsProxies. listEffectiveTags</code></li>
<li><code>compute. regionTargetHttpsProxies. listTagBindings</code></li>
<li><code>compute. regionTargetHttpsProxies. setSslCertificates</code></li>
<li><code>compute. regionTargetHttpsProxies. setUrlMap</code></li>
<li><code>compute. regionTargetHttpsProxies. update</code></li>
<li><code>compute. regionTargetHttpsProxies. use</code></li>
</ul>
<p><code>compute. regionTargetTcpProxies.*</code></p>
<ul>
<li><code>compute. regionTargetTcpProxies. attach</code></li>
<li><code>compute. regionTargetTcpProxies. create</code></li>
<li><code>compute. regionTargetTcpProxies. createTagBinding</code></li>
<li><code>compute. regionTargetTcpProxies. delete</code></li>
<li><code>compute. regionTargetTcpProxies. deleteTagBinding</code></li>
<li><code>compute. regionTargetTcpProxies. get</code></li>
<li><code>compute. regionTargetTcpProxies. list</code></li>
<li><code>compute. regionTargetTcpProxies. listEffectiveTags</code></li>
<li><code>compute. regionTargetTcpProxies. listTagBindings</code></li>
<li><code>compute. regionTargetTcpProxies. use</code></li>
</ul>
<p><code>compute.regionUrlMaps.*</code></p>
<ul>
<li><code>compute.regionUrlMaps.create</code></li>
<li><code>compute. regionUrlMaps. createTagBinding</code></li>
<li><code>compute.regionUrlMaps.delete</code></li>
<li><code>compute. regionUrlMaps. deleteTagBinding</code></li>
<li><code>compute.regionUrlMaps.get</code></li>
<li><code>compute. regionUrlMaps. invalidateCache</code></li>
<li><code>compute.regionUrlMaps.list</code></li>
<li><code>compute. regionUrlMaps. listEffectiveTags</code></li>
<li><code>compute. regionUrlMaps. listTagBindings</code></li>
<li><code>compute.regionUrlMaps.update</code></li>
<li><code>compute.regionUrlMaps.use</code></li>
<li><code>compute.regionUrlMaps.validate</code></li>
</ul>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.reservationBlocks.get</code></p>
<p><code>compute.reservationBlocks.list</code></p>
<p><code>compute. reservationConsumedInstances. list</code></p>
<p><code>compute.reservationSlots.*</code></p>
<ul>
<li><code>compute.reservationSlots.get</code></li>
<li><code>compute.reservationSlots.list</code></li>
<li><code>compute. reservationSlots. update</code></li>
</ul>
<p><code>compute.reservationSubBlocks.*</code></p>
<ul>
<li><code>compute. reservationSubBlocks. get</code></li>
<li><code>compute. reservationSubBlocks. list</code></li>
<li><code>compute. reservationSubBlocks. performMaintenance</code></li>
<li><code>compute. reservationSubBlocks. reportFaulty</code></li>
</ul>
<p><code>compute.reservations.get</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>compute. reservations. listEffectiveTags</code></p>
<p><code>compute. reservations. listTagBindings</code></p>
<p><code>compute.resourcePolicies.*</code></p>
<ul>
<li><code>compute. resourcePolicies. create</code></li>
<li><code>compute. resourcePolicies. delete</code></li>
<li><code>compute.resourcePolicies.get</code></li>
<li><code>compute. resourcePolicies. getIamPolicy</code></li>
<li><code>compute.resourcePolicies.list</code></li>
<li><code>compute. resourcePolicies. setIamPolicy</code></li>
<li><code>compute. resourcePolicies. update</code></li>
<li><code>compute.resourcePolicies.use</code></li>
<li><code>compute. resourcePolicies. useReadOnly</code></li>
</ul>
<p><code>compute.routers.*</code></p>
<ul>
<li><code>compute.routers.create</code></li>
<li><code>compute. routers. createTagBinding</code></li>
<li><code>compute.routers.delete</code></li>
<li><code>compute. routers. deleteRoutePolicy</code></li>
<li><code>compute. routers. deleteTagBinding</code></li>
<li><code>compute.routers.get</code></li>
<li><code>compute.routers.getRoutePolicy</code></li>
<li><code>compute.routers.list</code></li>
<li><code>compute.routers.listBgpRoutes</code></li>
<li><code>compute. routers. listEffectiveTags</code></li>
<li><code>compute. routers. listRoutePolicies</code></li>
<li><code>compute. routers. listTagBindings</code></li>
<li><code>compute.routers.update</code></li>
<li><code>compute. routers. updateRoutePolicy</code></li>
<li><code>compute.routers.use</code></li>
</ul>
<p><code>compute.routes.*</code></p>
<ul>
<li><code>compute.routes.create</code></li>
<li><code>compute. routes. createTagBinding</code></li>
<li><code>compute.routes.delete</code></li>
<li><code>compute. routes. deleteTagBinding</code></li>
<li><code>compute.routes.get</code></li>
<li><code>compute.routes.list</code></li>
<li><code>compute. routes. listEffectiveTags</code></li>
<li><code>compute.routes.listTagBindings</code></li>
</ul>
<p><code>compute.securityPolicies.get</code></p>
<p><code>compute.securityPolicies.list</code></p>
<p><code>compute. securityPolicies. listEffectiveTags</code></p>
<p><code>compute. securityPolicies. listTagBindings</code></p>
<p><code>compute.securityPolicies.use</code></p>
<p><code>compute.serviceAttachments.*</code></p>
<ul>
<li><code>compute. serviceAttachments. create</code></li>
<li><code>compute. serviceAttachments. createTagBinding</code></li>
<li><code>compute. serviceAttachments. delete</code></li>
<li><code>compute. serviceAttachments. deleteTagBinding</code></li>
<li><code>compute.serviceAttachments.get</code></li>
<li><code>compute. serviceAttachments. getIamPolicy</code></li>
<li><code>compute. serviceAttachments. list</code></li>
<li><code>compute. serviceAttachments. listEffectiveTags</code></li>
<li><code>compute. serviceAttachments. listTagBindings</code></li>
<li><code>compute. serviceAttachments. setIamPolicy</code></li>
<li><code>compute. serviceAttachments. update</code></li>
<li><code>compute.serviceAttachments.use</code></li>
</ul>
<p><code>compute.snapshotGroups.*</code></p>
<ul>
<li><code>compute.snapshotGroups.create</code></li>
<li><code>compute.snapshotGroups.delete</code></li>
<li><code>compute.snapshotGroups.get</code></li>
<li><code>compute. snapshotGroups. getIamPolicy</code></li>
<li><code>compute.snapshotGroups.list</code></li>
<li><code>compute. snapshotGroups. setIamPolicy</code></li>
<li><code>compute. snapshotGroups. useReadOnly</code></li>
</ul>
<p><code>compute.snapshots.*</code></p>
<ul>
<li><code>compute.snapshots.create</code></li>
<li><code>compute. snapshots. createTagBinding</code></li>
<li><code>compute.snapshots.delete</code></li>
<li><code>compute. snapshots. deleteTagBinding</code></li>
<li><code>compute.snapshots.get</code></li>
<li><code>compute. snapshots. getEffectiveRecycleBinRule</code></li>
<li><code>compute.snapshots.getIamPolicy</code></li>
<li><code>compute.snapshots.list</code></li>
<li><code>compute. snapshots. listEffectiveTags</code></li>
<li><code>compute. snapshots. listTagBindings</code></li>
<li><code>compute.snapshots.setIamPolicy</code></li>
<li><code>compute.snapshots.setLabels</code></li>
<li><code>compute.snapshots.updateKmsKey</code></li>
<li><code>compute.snapshots.useReadOnly</code></li>
</ul>
<p><code>compute.spotAssistants.get</code></p>
<p><code>compute.sslCertificates.get</code></p>
<p><code>compute.sslCertificates.list</code></p>
<p><code>compute. sslCertificates. listEffectiveTags</code></p>
<p><code>compute. sslCertificates. listTagBindings</code></p>
<p><code>compute.sslPolicies.*</code></p>
<ul>
<li><code>compute.sslPolicies.create</code></li>
<li><code>compute. sslPolicies. createTagBinding</code></li>
<li><code>compute.sslPolicies.delete</code></li>
<li><code>compute. sslPolicies. deleteTagBinding</code></li>
<li><code>compute.sslPolicies.get</code></li>
<li><code>compute. sslPolicies. getIamPolicy</code></li>
<li><code>compute.sslPolicies.list</code></li>
<li><code>compute. sslPolicies. listAvailableFeatures</code></li>
<li><code>compute. sslPolicies. listEffectiveTags</code></li>
<li><code>compute. sslPolicies. listTagBindings</code></li>
<li><code>compute. sslPolicies. setIamPolicy</code></li>
<li><code>compute.sslPolicies.update</code></li>
<li><code>compute.sslPolicies.use</code></li>
</ul>
<p><code>compute.storagePools.get</code></p>
<p><code>compute.storagePools.list</code></p>
<p><code>compute. storagePools. listEffectiveTags</code></p>
<p><code>compute. storagePools. listTagBindings</code></p>
<p><code>compute.storagePools.use</code></p>
<p><code>compute.subnetworks.*</code></p>
<ul>
<li><code>compute.subnetworks.create</code></li>
<li><code>compute. subnetworks. createTagBinding</code></li>
<li><code>compute.subnetworks.delete</code></li>
<li><code>compute. subnetworks. deleteTagBinding</code></li>
<li><code>compute. subnetworks. expandIpCidrRange</code></li>
<li><code>compute.subnetworks.get</code></li>
<li><code>compute. subnetworks. getIamPolicy</code></li>
<li><code>compute.subnetworks.list</code></li>
<li><code>compute. subnetworks. listEffectiveTags</code></li>
<li><code>compute. subnetworks. listTagBindings</code></li>
<li><code>compute.subnetworks.mirror</code></li>
<li><code>compute. subnetworks. setIamPolicy</code></li>
<li><code>compute. subnetworks. setPrivateIpGoogleAccess</code></li>
<li><code>compute.subnetworks.update</code></li>
<li><code>compute.subnetworks.use</code></li>
<li><code>compute. subnetworks. useExternalIp</code></li>
<li><code>compute. subnetworks. usePeerMigration</code></li>
</ul>
<p><code>compute.targetGrpcProxies.*</code></p>
<ul>
<li><code>compute. targetGrpcProxies. create</code></li>
<li><code>compute. targetGrpcProxies. createTagBinding</code></li>
<li><code>compute. targetGrpcProxies. delete</code></li>
<li><code>compute. targetGrpcProxies. deleteTagBinding</code></li>
<li><code>compute.targetGrpcProxies.get</code></li>
<li><code>compute.targetGrpcProxies.list</code></li>
<li><code>compute. targetGrpcProxies. listEffectiveTags</code></li>
<li><code>compute. targetGrpcProxies. listTagBindings</code></li>
<li><code>compute. targetGrpcProxies. update</code></li>
<li><code>compute.targetGrpcProxies.use</code></li>
</ul>
<p><code>compute.targetHttpProxies.*</code></p>
<ul>
<li><code>compute. targetHttpProxies. create</code></li>
<li><code>compute. targetHttpProxies. createTagBinding</code></li>
<li><code>compute. targetHttpProxies. delete</code></li>
<li><code>compute. targetHttpProxies. deleteTagBinding</code></li>
<li><code>compute.targetHttpProxies.get</code></li>
<li><code>compute.targetHttpProxies.list</code></li>
<li><code>compute. targetHttpProxies. listEffectiveTags</code></li>
<li><code>compute. targetHttpProxies. listTagBindings</code></li>
<li><code>compute. targetHttpProxies. setUrlMap</code></li>
<li><code>compute. targetHttpProxies. update</code></li>
<li><code>compute.targetHttpProxies.use</code></li>
</ul>
<p><code>compute.targetHttpsProxies.*</code></p>
<ul>
<li><code>compute. targetHttpsProxies. create</code></li>
<li><code>compute. targetHttpsProxies. createTagBinding</code></li>
<li><code>compute. targetHttpsProxies. delete</code></li>
<li><code>compute. targetHttpsProxies. deleteTagBinding</code></li>
<li><code>compute.targetHttpsProxies.get</code></li>
<li><code>compute. targetHttpsProxies. list</code></li>
<li><code>compute. targetHttpsProxies. listEffectiveTags</code></li>
<li><code>compute. targetHttpsProxies. listTagBindings</code></li>
<li><code>compute. targetHttpsProxies. setCertificateMap</code></li>
<li><code>compute. targetHttpsProxies. setQuicOverride</code></li>
<li><code>compute. targetHttpsProxies. setSslCertificates</code></li>
<li><code>compute. targetHttpsProxies. setSslPolicy</code></li>
<li><code>compute. targetHttpsProxies. setUrlMap</code></li>
<li><code>compute. targetHttpsProxies. update</code></li>
<li><code>compute.targetHttpsProxies.use</code></li>
</ul>
<p><code>compute.targetInstances.*</code></p>
<ul>
<li><code>compute.targetInstances.create</code></li>
<li><code>compute. targetInstances. createTagBinding</code></li>
<li><code>compute.targetInstances.delete</code></li>
<li><code>compute. targetInstances. deleteTagBinding</code></li>
<li><code>compute.targetInstances.get</code></li>
<li><code>compute.targetInstances.list</code></li>
<li><code>compute. targetInstances. listEffectiveTags</code></li>
<li><code>compute. targetInstances. listTagBindings</code></li>
<li><code>compute. targetInstances. setSecurityPolicy</code></li>
<li><code>compute.targetInstances.use</code></li>
</ul>
<p><code>compute.targetPools.*</code></p>
<ul>
<li><code>compute. targetPools. addHealthCheck</code></li>
<li><code>compute. targetPools. addInstance</code></li>
<li><code>compute.targetPools.create</code></li>
<li><code>compute. targetPools. createTagBinding</code></li>
<li><code>compute.targetPools.delete</code></li>
<li><code>compute. targetPools. deleteTagBinding</code></li>
<li><code>compute.targetPools.get</code></li>
<li><code>compute.targetPools.list</code></li>
<li><code>compute. targetPools. listEffectiveTags</code></li>
<li><code>compute. targetPools. listTagBindings</code></li>
<li><code>compute. targetPools. removeHealthCheck</code></li>
<li><code>compute. targetPools. removeInstance</code></li>
<li><code>compute. targetPools. setSecurityPolicy</code></li>
<li><code>compute.targetPools.update</code></li>
<li><code>compute.targetPools.use</code></li>
</ul>
<p><code>compute.targetSslProxies.*</code></p>
<ul>
<li><code>compute. targetSslProxies. create</code></li>
<li><code>compute. targetSslProxies. createTagBinding</code></li>
<li><code>compute. targetSslProxies. delete</code></li>
<li><code>compute. targetSslProxies. deleteTagBinding</code></li>
<li><code>compute.targetSslProxies.get</code></li>
<li><code>compute.targetSslProxies.list</code></li>
<li><code>compute. targetSslProxies. listEffectiveTags</code></li>
<li><code>compute. targetSslProxies. listTagBindings</code></li>
<li><code>compute. targetSslProxies. setBackendService</code></li>
<li><code>compute. targetSslProxies. setCertificateMap</code></li>
<li><code>compute. targetSslProxies. setProxyHeader</code></li>
<li><code>compute. targetSslProxies. setSslCertificates</code></li>
<li><code>compute. targetSslProxies. setSslPolicy</code></li>
<li><code>compute. targetSslProxies. update</code></li>
<li><code>compute.targetSslProxies.use</code></li>
</ul>
<p><code>compute.targetTcpProxies.*</code></p>
<ul>
<li><code>compute. targetTcpProxies. attach</code></li>
<li><code>compute. targetTcpProxies. create</code></li>
<li><code>compute. targetTcpProxies. createTagBinding</code></li>
<li><code>compute. targetTcpProxies. delete</code></li>
<li><code>compute. targetTcpProxies. deleteTagBinding</code></li>
<li><code>compute.targetTcpProxies.get</code></li>
<li><code>compute.targetTcpProxies.list</code></li>
<li><code>compute. targetTcpProxies. listEffectiveTags</code></li>
<li><code>compute. targetTcpProxies. listTagBindings</code></li>
<li><code>compute. targetTcpProxies. update</code></li>
<li><code>compute.targetTcpProxies.use</code></li>
</ul>
<p><code>compute.targetVpnGateways.*</code></p>
<ul>
<li><code>compute. targetVpnGateways. create</code></li>
<li><code>compute. targetVpnGateways. createTagBinding</code></li>
<li><code>compute. targetVpnGateways. delete</code></li>
<li><code>compute. targetVpnGateways. deleteTagBinding</code></li>
<li><code>compute.targetVpnGateways.get</code></li>
<li><code>compute.targetVpnGateways.list</code></li>
<li><code>compute. targetVpnGateways. listEffectiveTags</code></li>
<li><code>compute. targetVpnGateways. listTagBindings</code></li>
<li><code>compute. targetVpnGateways. setLabels</code></li>
<li><code>compute.targetVpnGateways.use</code></li>
</ul>
<p><code>compute.urlMaps.*</code></p>
<ul>
<li><code>compute.urlMaps.create</code></li>
<li><code>compute. urlMaps. createTagBinding</code></li>
<li><code>compute.urlMaps.delete</code></li>
<li><code>compute. urlMaps. deleteTagBinding</code></li>
<li><code>compute.urlMaps.get</code></li>
<li><code>compute. urlMaps. invalidateCache</code></li>
<li><code>compute.urlMaps.list</code></li>
<li><code>compute. urlMaps. listEffectiveTags</code></li>
<li><code>compute. urlMaps. listTagBindings</code></li>
<li><code>compute.urlMaps.update</code></li>
<li><code>compute.urlMaps.use</code></li>
<li><code>compute.urlMaps.validate</code></li>
</ul>
<p><code>compute.vpnGateways.*</code></p>
<ul>
<li><code>compute.vpnGateways.create</code></li>
<li><code>compute. vpnGateways. createTagBinding</code></li>
<li><code>compute.vpnGateways.delete</code></li>
<li><code>compute. vpnGateways. deleteTagBinding</code></li>
<li><code>compute.vpnGateways.get</code></li>
<li><code>compute.vpnGateways.list</code></li>
<li><code>compute. vpnGateways. listEffectiveTags</code></li>
<li><code>compute. vpnGateways. listTagBindings</code></li>
<li><code>compute.vpnGateways.setLabels</code></li>
<li><code>compute.vpnGateways.use</code></li>
</ul>
<p><code>compute.vpnTunnels.*</code></p>
<ul>
<li><code>compute.vpnTunnels.create</code></li>
<li><code>compute. vpnTunnels. createTagBinding</code></li>
<li><code>compute.vpnTunnels.delete</code></li>
<li><code>compute. vpnTunnels. deleteTagBinding</code></li>
<li><code>compute.vpnTunnels.get</code></li>
<li><code>compute.vpnTunnels.list</code></li>
<li><code>compute. vpnTunnels. listEffectiveTags</code></li>
<li><code>compute. vpnTunnels. listTagBindings</code></li>
<li><code>compute.vpnTunnels.setLabels</code></li>
</ul>
<p><code>compute.wireGroups.*</code></p>
<ul>
<li><code>compute.wireGroups.create</code></li>
<li><code>compute.wireGroups.delete</code></li>
<li><code>compute.wireGroups.get</code></li>
<li><code>compute.wireGroups.list</code></li>
<li><code>compute.wireGroups.update</code></li>
</ul>
<p><code>compute.zoneOperations.get</code></p>
<p><code>compute.zoneOperations.list</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>container.*</code></p>
<ul>
<li><code>container.apiServices.create</code></li>
<li><code>container.apiServices.delete</code></li>
<li><code>container.apiServices.get</code></li>
<li><code>container. apiServices. getStatus</code></li>
<li><code>container.apiServices.list</code></li>
<li><code>container.apiServices.update</code></li>
<li><code>container. apiServices. updateStatus</code></li>
<li><code>container.auditSinks.create</code></li>
<li><code>container.auditSinks.delete</code></li>
<li><code>container.auditSinks.get</code></li>
<li><code>container.auditSinks.list</code></li>
<li><code>container.auditSinks.update</code></li>
<li><code>container. backendConfigs. create</code></li>
<li><code>container. backendConfigs. delete</code></li>
<li><code>container.backendConfigs.get</code></li>
<li><code>container.backendConfigs.list</code></li>
<li><code>container. backendConfigs. update</code></li>
<li><code>container.bindings.create</code></li>
<li><code>container.bindings.delete</code></li>
<li><code>container.bindings.get</code></li>
<li><code>container.bindings.list</code></li>
<li><code>container.bindings.update</code></li>
<li><code>container. certificateSigningRequests. approve</code></li>
<li><code>container. certificateSigningRequests. create</code></li>
<li><code>container. certificateSigningRequests. delete</code></li>
<li><code>container. certificateSigningRequests. get</code></li>
<li><code>container. certificateSigningRequests. getStatus</code></li>
<li><code>container. certificateSigningRequests. list</code></li>
<li><code>container. certificateSigningRequests. update</code></li>
<li><code>container. certificateSigningRequests. updateStatus</code></li>
<li><code>container. clusterRoleBindings. create</code></li>
<li><code>container. clusterRoleBindings. delete</code></li>
<li><code>container. clusterRoleBindings. get</code></li>
<li><code>container. clusterRoleBindings. list</code></li>
<li><code>container. clusterRoleBindings. update</code></li>
<li><code>container.clusterRoles.bind</code></li>
<li><code>container.clusterRoles.create</code></li>
<li><code>container.clusterRoles.delete</code></li>
<li><code>container. clusterRoles. escalate</code></li>
<li><code>container.clusterRoles.get</code></li>
<li><code>container.clusterRoles.list</code></li>
<li><code>container.clusterRoles.update</code></li>
<li><code>container.clusters.connect</code></li>
<li><code>container.clusters.create</code></li>
<li><code>container. clusters. createTagBinding</code></li>
<li><code>container.clusters.delete</code></li>
<li><code>container. clusters. deleteTagBinding</code></li>
<li><code>container.clusters.get</code></li>
<li><code>container. clusters. getCredentials</code></li>
<li><code>container.clusters.impersonate</code></li>
<li><code>container.clusters.list</code></li>
<li><code>container. clusters. listEffectiveTags</code></li>
<li><code>container. clusters. listTagBindings</code></li>
<li><code>container.clusters.update</code></li>
<li><code>container. componentStatuses. get</code></li>
<li><code>container. componentStatuses. list</code></li>
<li><code>container.configMaps.create</code></li>
<li><code>container.configMaps.delete</code></li>
<li><code>container.configMaps.get</code></li>
<li><code>container.configMaps.list</code></li>
<li><code>container.configMaps.update</code></li>
<li><code>container. controllerRevisions. create</code></li>
<li><code>container. controllerRevisions. delete</code></li>
<li><code>container. controllerRevisions. get</code></li>
<li><code>container. controllerRevisions. list</code></li>
<li><code>container. controllerRevisions. update</code></li>
<li><code>container.cronJobs.create</code></li>
<li><code>container.cronJobs.delete</code></li>
<li><code>container.cronJobs.get</code></li>
<li><code>container.cronJobs.getStatus</code></li>
<li><code>container.cronJobs.list</code></li>
<li><code>container.cronJobs.update</code></li>
<li><code>container. cronJobs. updateStatus</code></li>
<li><code>container.csiDrivers.create</code></li>
<li><code>container.csiDrivers.delete</code></li>
<li><code>container.csiDrivers.get</code></li>
<li><code>container.csiDrivers.list</code></li>
<li><code>container.csiDrivers.update</code></li>
<li><code>container.csiNodeInfos.create</code></li>
<li><code>container.csiNodeInfos.delete</code></li>
<li><code>container.csiNodeInfos.get</code></li>
<li><code>container.csiNodeInfos.list</code></li>
<li><code>container.csiNodeInfos.update</code></li>
<li><code>container.csiNodes.create</code></li>
<li><code>container.csiNodes.delete</code></li>
<li><code>container.csiNodes.get</code></li>
<li><code>container.csiNodes.list</code></li>
<li><code>container.csiNodes.update</code></li>
<li><code>container. customResourceDefinitions. create</code></li>
<li><code>container. customResourceDefinitions. delete</code></li>
<li><code>container. customResourceDefinitions. get</code></li>
<li><code>container. customResourceDefinitions. getStatus</code></li>
<li><code>container. customResourceDefinitions. list</code></li>
<li><code>container. customResourceDefinitions. update</code></li>
<li><code>container. customResourceDefinitions. updateStatus</code></li>
<li><code>container.daemonSets.create</code></li>
<li><code>container.daemonSets.delete</code></li>
<li><code>container.daemonSets.get</code></li>
<li><code>container.daemonSets.getStatus</code></li>
<li><code>container.daemonSets.list</code></li>
<li><code>container.daemonSets.update</code></li>
<li><code>container. daemonSets. updateStatus</code></li>
<li><code>container.deployments.create</code></li>
<li><code>container.deployments.delete</code></li>
<li><code>container.deployments.get</code></li>
<li><code>container.deployments.getScale</code></li>
<li><code>container. deployments. getStatus</code></li>
<li><code>container.deployments.list</code></li>
<li><code>container.deployments.rollback</code></li>
<li><code>container.deployments.update</code></li>
<li><code>container. deployments. updateScale</code></li>
<li><code>container. deployments. updateStatus</code></li>
<li><code>container. endpointSlices. create</code></li>
<li><code>container. endpointSlices. delete</code></li>
<li><code>container.endpointSlices.get</code></li>
<li><code>container.endpointSlices.list</code></li>
<li><code>container. endpointSlices. update</code></li>
<li><code>container.endpoints.create</code></li>
<li><code>container.endpoints.delete</code></li>
<li><code>container.endpoints.get</code></li>
<li><code>container.endpoints.list</code></li>
<li><code>container.endpoints.update</code></li>
<li><code>container.events.create</code></li>
<li><code>container.events.delete</code></li>
<li><code>container.events.get</code></li>
<li><code>container.events.list</code></li>
<li><code>container.events.update</code></li>
<li><code>container. frontendConfigs. create</code></li>
<li><code>container. frontendConfigs. delete</code></li>
<li><code>container.frontendConfigs.get</code></li>
<li><code>container.frontendConfigs.list</code></li>
<li><code>container. frontendConfigs. update</code></li>
<li><code>container. horizontalPodAutoscalers. create</code></li>
<li><code>container. horizontalPodAutoscalers. delete</code></li>
<li><code>container. horizontalPodAutoscalers. get</code></li>
<li><code>container. horizontalPodAutoscalers. getStatus</code></li>
<li><code>container. horizontalPodAutoscalers. list</code></li>
<li><code>container. horizontalPodAutoscalers. update</code></li>
<li><code>container. horizontalPodAutoscalers. updateStatus</code></li>
<li><code>container.hostServiceAgent.use</code></li>
<li><code>container.ingresses.create</code></li>
<li><code>container.ingresses.delete</code></li>
<li><code>container.ingresses.get</code></li>
<li><code>container.ingresses.getStatus</code></li>
<li><code>container.ingresses.list</code></li>
<li><code>container.ingresses.update</code></li>
<li><code>container. ingresses. updateStatus</code></li>
<li><code>container. initializerConfigurations. create</code></li>
<li><code>container. initializerConfigurations. delete</code></li>
<li><code>container. initializerConfigurations. get</code></li>
<li><code>container. initializerConfigurations. list</code></li>
<li><code>container. initializerConfigurations. update</code></li>
<li><code>container.jobs.create</code></li>
<li><code>container.jobs.delete</code></li>
<li><code>container.jobs.get</code></li>
<li><code>container.jobs.getStatus</code></li>
<li><code>container.jobs.list</code></li>
<li><code>container.jobs.update</code></li>
<li><code>container.jobs.updateStatus</code></li>
<li><code>container.leases.create</code></li>
<li><code>container.leases.delete</code></li>
<li><code>container.leases.get</code></li>
<li><code>container.leases.list</code></li>
<li><code>container.leases.update</code></li>
<li><code>container.limitRanges.create</code></li>
<li><code>container.limitRanges.delete</code></li>
<li><code>container.limitRanges.get</code></li>
<li><code>container.limitRanges.list</code></li>
<li><code>container.limitRanges.update</code></li>
<li><code>container. localSubjectAccessReviews. create</code></li>
<li><code>container. localSubjectAccessReviews. list</code></li>
<li><code>container. managedCertificates. create</code></li>
<li><code>container. managedCertificates. delete</code></li>
<li><code>container. managedCertificates. get</code></li>
<li><code>container. managedCertificates. list</code></li>
<li><code>container. managedCertificates. update</code></li>
<li><code>container. mutatingWebhookConfigurations. create</code></li>
<li><code>container. mutatingWebhookConfigurations. delete</code></li>
<li><code>container. mutatingWebhookConfigurations. get</code></li>
<li><code>container. mutatingWebhookConfigurations. list</code></li>
<li><code>container. mutatingWebhookConfigurations. update</code></li>
<li><code>container.namespaces.create</code></li>
<li><code>container.namespaces.delete</code></li>
<li><code>container.namespaces.finalize</code></li>
<li><code>container.namespaces.get</code></li>
<li><code>container.namespaces.getStatus</code></li>
<li><code>container.namespaces.list</code></li>
<li><code>container.namespaces.update</code></li>
<li><code>container. namespaces. updateStatus</code></li>
<li><code>container. networkPolicies. create</code></li>
<li><code>container. networkPolicies. delete</code></li>
<li><code>container.networkPolicies.get</code></li>
<li><code>container.networkPolicies.list</code></li>
<li><code>container. networkPolicies. update</code></li>
<li><code>container.nodes.create</code></li>
<li><code>container.nodes.delete</code></li>
<li><code>container.nodes.get</code></li>
<li><code>container.nodes.getStatus</code></li>
<li><code>container.nodes.list</code></li>
<li><code>container.nodes.proxy</code></li>
<li><code>container.nodes.update</code></li>
<li><code>container.nodes.updateStatus</code></li>
<li><code>container.operations.get</code></li>
<li><code>container.operations.list</code></li>
<li><code>container. persistentVolumeClaims. create</code></li>
<li><code>container. persistentVolumeClaims. delete</code></li>
<li><code>container. persistentVolumeClaims. get</code></li>
<li><code>container. persistentVolumeClaims. getStatus</code></li>
<li><code>container. persistentVolumeClaims. list</code></li>
<li><code>container. persistentVolumeClaims. update</code></li>
<li><code>container. persistentVolumeClaims. updateStatus</code></li>
<li><code>container. persistentVolumes. create</code></li>
<li><code>container. persistentVolumes. delete</code></li>
<li><code>container. persistentVolumes. get</code></li>
<li><code>container. persistentVolumes. getStatus</code></li>
<li><code>container. persistentVolumes. list</code></li>
<li><code>container. persistentVolumes. update</code></li>
<li><code>container. persistentVolumes. updateStatus</code></li>
<li><code>container.petSets.create</code></li>
<li><code>container.petSets.delete</code></li>
<li><code>container.petSets.get</code></li>
<li><code>container.petSets.list</code></li>
<li><code>container.petSets.update</code></li>
<li><code>container.petSets.updateStatus</code></li>
<li><code>container. podDisruptionBudgets. create</code></li>
<li><code>container. podDisruptionBudgets. delete</code></li>
<li><code>container. podDisruptionBudgets. get</code></li>
<li><code>container. podDisruptionBudgets. getStatus</code></li>
<li><code>container. podDisruptionBudgets. list</code></li>
<li><code>container. podDisruptionBudgets. update</code></li>
<li><code>container. podDisruptionBudgets. updateStatus</code></li>
<li><code>container.podPresets.create</code></li>
<li><code>container.podPresets.delete</code></li>
<li><code>container.podPresets.get</code></li>
<li><code>container.podPresets.list</code></li>
<li><code>container.podPresets.update</code></li>
<li><code>container. podSecurityPolicies. create</code></li>
<li><code>container. podSecurityPolicies. delete</code></li>
<li><code>container. podSecurityPolicies. get</code></li>
<li><code>container. podSecurityPolicies. list</code></li>
<li><code>container. podSecurityPolicies. update</code></li>
<li><code>container. podSecurityPolicies. use</code></li>
<li><code>container.podTemplates.create</code></li>
<li><code>container.podTemplates.delete</code></li>
<li><code>container.podTemplates.get</code></li>
<li><code>container.podTemplates.list</code></li>
<li><code>container.podTemplates.update</code></li>
<li><code>container.pods.attach</code></li>
<li><code>container.pods.create</code></li>
<li><code>container.pods.delete</code></li>
<li><code>container.pods.evict</code></li>
<li><code>container.pods.exec</code></li>
<li><code>container.pods.get</code></li>
<li><code>container.pods.getLogs</code></li>
<li><code>container.pods.getStatus</code></li>
<li><code>container.pods.initialize</code></li>
<li><code>container.pods.list</code></li>
<li><code>container.pods.portForward</code></li>
<li><code>container.pods.proxy</code></li>
<li><code>container.pods.update</code></li>
<li><code>container.pods.updateStatus</code></li>
<li><code>container. priorityClasses. create</code></li>
<li><code>container. priorityClasses. delete</code></li>
<li><code>container.priorityClasses.get</code></li>
<li><code>container.priorityClasses.list</code></li>
<li><code>container. priorityClasses. update</code></li>
<li><code>container.replicaSets.create</code></li>
<li><code>container.replicaSets.delete</code></li>
<li><code>container.replicaSets.get</code></li>
<li><code>container.replicaSets.getScale</code></li>
<li><code>container. replicaSets. getStatus</code></li>
<li><code>container.replicaSets.list</code></li>
<li><code>container.replicaSets.update</code></li>
<li><code>container. replicaSets. updateScale</code></li>
<li><code>container. replicaSets. updateStatus</code></li>
<li><code>container. replicationControllers. create</code></li>
<li><code>container. replicationControllers. delete</code></li>
<li><code>container. replicationControllers. get</code></li>
<li><code>container. replicationControllers. getScale</code></li>
<li><code>container. replicationControllers. getStatus</code></li>
<li><code>container. replicationControllers. list</code></li>
<li><code>container. replicationControllers. update</code></li>
<li><code>container. replicationControllers. updateScale</code></li>
<li><code>container. replicationControllers. updateStatus</code></li>
<li><code>container. resourceQuotas. create</code></li>
<li><code>container. resourceQuotas. delete</code></li>
<li><code>container.resourceQuotas.get</code></li>
<li><code>container. resourceQuotas. getStatus</code></li>
<li><code>container.resourceQuotas.list</code></li>
<li><code>container. resourceQuotas. update</code></li>
<li><code>container. resourceQuotas. updateStatus</code></li>
<li><code>container.roleBindings.create</code></li>
<li><code>container.roleBindings.delete</code></li>
<li><code>container.roleBindings.get</code></li>
<li><code>container.roleBindings.list</code></li>
<li><code>container.roleBindings.update</code></li>
<li><code>container.roles.bind</code></li>
<li><code>container.roles.create</code></li>
<li><code>container.roles.delete</code></li>
<li><code>container.roles.escalate</code></li>
<li><code>container.roles.get</code></li>
<li><code>container.roles.list</code></li>
<li><code>container.roles.update</code></li>
<li><code>container. runtimeClasses. create</code></li>
<li><code>container. runtimeClasses. delete</code></li>
<li><code>container.runtimeClasses.get</code></li>
<li><code>container.runtimeClasses.list</code></li>
<li><code>container. runtimeClasses. update</code></li>
<li><code>container.scheduledJobs.create</code></li>
<li><code>container.scheduledJobs.delete</code></li>
<li><code>container.scheduledJobs.get</code></li>
<li><code>container.scheduledJobs.list</code></li>
<li><code>container.scheduledJobs.update</code></li>
<li><code>container. scheduledJobs. updateStatus</code></li>
<li><code>container.secrets.create</code></li>
<li><code>container.secrets.delete</code></li>
<li><code>container.secrets.get</code></li>
<li><code>container.secrets.list</code></li>
<li><code>container.secrets.update</code></li>
<li><code>container. selfSubjectAccessReviews. create</code></li>
<li><code>container. selfSubjectAccessReviews. list</code></li>
<li><code>container. selfSubjectRulesReviews. create</code></li>
<li><code>container. serviceAccounts. create</code></li>
<li><code>container. serviceAccounts. createToken</code></li>
<li><code>container. serviceAccounts. delete</code></li>
<li><code>container.serviceAccounts.get</code></li>
<li><code>container.serviceAccounts.list</code></li>
<li><code>container. serviceAccounts. update</code></li>
<li><code>container.services.create</code></li>
<li><code>container.services.delete</code></li>
<li><code>container.services.get</code></li>
<li><code>container.services.getStatus</code></li>
<li><code>container.services.list</code></li>
<li><code>container.services.proxy</code></li>
<li><code>container.services.update</code></li>
<li><code>container. services. updateStatus</code></li>
<li><code>container.statefulSets.create</code></li>
<li><code>container.statefulSets.delete</code></li>
<li><code>container.statefulSets.get</code></li>
<li><code>container. statefulSets. getScale</code></li>
<li><code>container. statefulSets. getStatus</code></li>
<li><code>container.statefulSets.list</code></li>
<li><code>container.statefulSets.update</code></li>
<li><code>container. statefulSets. updateScale</code></li>
<li><code>container. statefulSets. updateStatus</code></li>
<li><code>container. storageClasses. create</code></li>
<li><code>container. storageClasses. delete</code></li>
<li><code>container.storageClasses.get</code></li>
<li><code>container.storageClasses.list</code></li>
<li><code>container. storageClasses. update</code></li>
<li><code>container.storageStates.create</code></li>
<li><code>container.storageStates.delete</code></li>
<li><code>container.storageStates.get</code></li>
<li><code>container. storageStates. getStatus</code></li>
<li><code>container.storageStates.list</code></li>
<li><code>container.storageStates.update</code></li>
<li><code>container. storageStates. updateStatus</code></li>
<li><code>container. storageVersionMigrations. create</code></li>
<li><code>container. storageVersionMigrations. delete</code></li>
<li><code>container. storageVersionMigrations. get</code></li>
<li><code>container. storageVersionMigrations. getStatus</code></li>
<li><code>container. storageVersionMigrations. list</code></li>
<li><code>container. storageVersionMigrations. update</code></li>
<li><code>container. storageVersionMigrations. updateStatus</code></li>
<li><code>container. subjectAccessReviews. create</code></li>
<li><code>container. subjectAccessReviews. list</code></li>
<li><code>container. thirdPartyObjects. create</code></li>
<li><code>container. thirdPartyObjects. delete</code></li>
<li><code>container. thirdPartyObjects. get</code></li>
<li><code>container. thirdPartyObjects. list</code></li>
<li><code>container. thirdPartyObjects. update</code></li>
<li><code>container. thirdPartyResources. create</code></li>
<li><code>container. thirdPartyResources. delete</code></li>
<li><code>container. thirdPartyResources. get</code></li>
<li><code>container. thirdPartyResources. list</code></li>
<li><code>container. thirdPartyResources. update</code></li>
<li><code>container.tokenReviews.create</code></li>
<li><code>container.updateInfos.create</code></li>
<li><code>container.updateInfos.delete</code></li>
<li><code>container.updateInfos.get</code></li>
<li><code>container.updateInfos.list</code></li>
<li><code>container.updateInfos.update</code></li>
<li><code>container. validatingWebhookConfigurations. create</code></li>
<li><code>container. validatingWebhookConfigurations. delete</code></li>
<li><code>container. validatingWebhookConfigurations. get</code></li>
<li><code>container. validatingWebhookConfigurations. list</code></li>
<li><code>container. validatingWebhookConfigurations. update</code></li>
<li><code>container. volumeAttachments. create</code></li>
<li><code>container. volumeAttachments. delete</code></li>
<li><code>container. volumeAttachments. get</code></li>
<li><code>container. volumeAttachments. getStatus</code></li>
<li><code>container. volumeAttachments. list</code></li>
<li><code>container. volumeAttachments. update</code></li>
<li><code>container. volumeAttachments. updateStatus</code></li>
<li><code>container. volumeSnapshotClasses. create</code></li>
<li><code>container. volumeSnapshotClasses. delete</code></li>
<li><code>container. volumeSnapshotClasses. get</code></li>
<li><code>container. volumeSnapshotClasses. list</code></li>
<li><code>container. volumeSnapshotClasses. update</code></li>
<li><code>container. volumeSnapshotContents. create</code></li>
<li><code>container. volumeSnapshotContents. delete</code></li>
<li><code>container. volumeSnapshotContents. get</code></li>
<li><code>container. volumeSnapshotContents. getStatus</code></li>
<li><code>container. volumeSnapshotContents. list</code></li>
<li><code>container. volumeSnapshotContents. update</code></li>
<li><code>container. volumeSnapshotContents. updateStatus</code></li>
<li><code>container. volumeSnapshots. create</code></li>
<li><code>container. volumeSnapshots. delete</code></li>
<li><code>container.volumeSnapshots.get</code></li>
<li><code>container. volumeSnapshots. getStatus</code></li>
<li><code>container.volumeSnapshots.list</code></li>
<li><code>container. volumeSnapshots. update</code></li>
<li><code>container. volumeSnapshots. updateStatus</code></li>
</ul>
<p><code>databasesconsole.locations.*</code></p>
<ul>
<li><code>databasesconsole.locations.get</code></li>
<li><code>databasesconsole. locations. list</code></li>
</ul>
<p><code>databasesconsole. studioQueries.*</code></p>
<ul>
<li><code>databasesconsole. studioQueries. create</code></li>
<li><code>databasesconsole. studioQueries. delete</code></li>
<li><code>databasesconsole. studioQueries. get</code></li>
<li><code>databasesconsole. studioQueries. list</code></li>
<li><code>databasesconsole. studioQueries. search</code></li>
<li><code>databasesconsole. studioQueries. update</code></li>
</ul>
<p><code>deploymentmanager. compositeTypes.*</code></p>
<ul>
<li><code>deploymentmanager. compositeTypes. create</code></li>
<li><code>deploymentmanager. compositeTypes. delete</code></li>
<li><code>deploymentmanager. compositeTypes. get</code></li>
<li><code>deploymentmanager. compositeTypes. list</code></li>
<li><code>deploymentmanager. compositeTypes. update</code></li>
</ul>
<p><code>deploymentmanager. deployments. cancelPreview</code></p>
<p><code>deploymentmanager. deployments. create</code></p>
<p><code>deploymentmanager. deployments. delete</code></p>
<p><code>deploymentmanager. deployments. get</code></p>
<p><code>deploymentmanager. deployments. list</code></p>
<p><code>deploymentmanager. deployments. stop</code></p>
<p><code>deploymentmanager. deployments. update</code></p>
<p><code>deploymentmanager.manifests.*</code></p>
<ul>
<li><code>deploymentmanager. manifests. get</code></li>
<li><code>deploymentmanager. manifests. list</code></li>
</ul>
<p><code>deploymentmanager.operations.*</code></p>
<ul>
<li><code>deploymentmanager. operations. get</code></li>
<li><code>deploymentmanager. operations. list</code></li>
</ul>
<p><code>deploymentmanager.resources.*</code></p>
<ul>
<li><code>deploymentmanager. resources. get</code></li>
<li><code>deploymentmanager. resources. list</code></li>
</ul>
<p><code>deploymentmanager. typeProviders.*</code></p>
<ul>
<li><code>deploymentmanager. typeProviders. create</code></li>
<li><code>deploymentmanager. typeProviders. delete</code></li>
<li><code>deploymentmanager. typeProviders. get</code></li>
<li><code>deploymentmanager. typeProviders. getType</code></li>
<li><code>deploymentmanager. typeProviders. list</code></li>
<li><code>deploymentmanager. typeProviders. listTypes</code></li>
<li><code>deploymentmanager. typeProviders. update</code></li>
</ul>
<p><code>deploymentmanager.types.*</code></p>
<ul>
<li><code>deploymentmanager.types.create</code></li>
<li><code>deploymentmanager.types.delete</code></li>
<li><code>deploymentmanager.types.get</code></li>
<li><code>deploymentmanager.types.list</code></li>
<li><code>deploymentmanager.types.update</code></li>
</ul>
<p><code>dns.managedZones.get</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns. networks. targetWithPeeringZone</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>iam. serviceAccounts. getOpenIdToken</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>logging.buckets.create</code></p>
<p><code>logging. buckets. createTagBinding</code></p>
<p><code>logging.buckets.delete</code></p>
<p><code>logging. buckets. deleteTagBinding</code></p>
<p><code>logging.buckets.get</code></p>
<p><code>logging.buckets.list</code></p>
<p><code>logging. buckets. listEffectiveTags</code></p>
<p><code>logging. buckets. listTagBindings</code></p>
<p><code>logging.buckets.undelete</code></p>
<p><code>logging.buckets.update</code></p>
<p><code>logging.exclusions.*</code></p>
<ul>
<li><code>logging.exclusions.create</code></li>
<li><code>logging.exclusions.delete</code></li>
<li><code>logging.exclusions.get</code></li>
<li><code>logging.exclusions.list</code></li>
<li><code>logging.exclusions.update</code></li>
</ul>
<p><code>logging.links.*</code></p>
<ul>
<li><code>logging.links.create</code></li>
<li><code>logging.links.delete</code></li>
<li><code>logging.links.get</code></li>
<li><code>logging.links.list</code></li>
</ul>
<p><code>logging.locations.*</code></p>
<ul>
<li><code>logging.locations.get</code></li>
<li><code>logging.locations.list</code></li>
</ul>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>logging.logMetrics.*</code></p>
<ul>
<li><code>logging.logMetrics.create</code></li>
<li><code>logging.logMetrics.delete</code></li>
<li><code>logging.logMetrics.get</code></li>
<li><code>logging.logMetrics.list</code></li>
<li><code>logging.logMetrics.update</code></li>
</ul>
<p><code>logging.logScopes.*</code></p>
<ul>
<li><code>logging.logScopes.create</code></li>
<li><code>logging.logScopes.delete</code></li>
<li><code>logging.logScopes.get</code></li>
<li><code>logging.logScopes.list</code></li>
<li><code>logging.logScopes.update</code></li>
</ul>
<p><code>logging.logServiceIndexes.list</code></p>
<p><code>logging.logServices.list</code></p>
<p><code>logging.logs.list</code></p>
<p><code>logging.notificationRules.*</code></p>
<ul>
<li><code>logging. notificationRules. create</code></li>
<li><code>logging. notificationRules. delete</code></li>
<li><code>logging.notificationRules.get</code></li>
<li><code>logging.notificationRules.list</code></li>
<li><code>logging. notificationRules. update</code></li>
</ul>
<p><code>logging.operations.*</code></p>
<ul>
<li><code>logging.operations.cancel</code></li>
<li><code>logging.operations.get</code></li>
<li><code>logging.operations.list</code></li>
</ul>
<p><code>logging.settings.*</code></p>
<ul>
<li><code>logging.settings.get</code></li>
<li><code>logging.settings.update</code></li>
</ul>
<p><code>logging.sinks.*</code></p>
<ul>
<li><code>logging.sinks.create</code></li>
<li><code>logging.sinks.delete</code></li>
<li><code>logging.sinks.get</code></li>
<li><code>logging.sinks.list</code></li>
<li><code>logging.sinks.update</code></li>
</ul>
<p><code>logging.sqlAlerts.*</code></p>
<ul>
<li><code>logging.sqlAlerts.create</code></li>
<li><code>logging.sqlAlerts.update</code></li>
</ul>
<p><code>logging.views.create</code></p>
<p><code>logging.views.delete</code></p>
<p><code>logging.views.get</code></p>
<p><code>logging.views.getIamPolicy</code></p>
<p><code>logging.views.list</code></p>
<p><code>logging.views.update</code></p>
<p><code>monitoring.alertPolicies.get</code></p>
<p><code>monitoring.alertPolicies.list</code></p>
<p><code>monitoring. alertPolicies. listEffectiveTags</code></p>
<p><code>monitoring. alertPolicies. listTagBindings</code></p>
<p><code>monitoring.alerts.*</code></p>
<ul>
<li><code>monitoring.alerts.get</code></li>
<li><code>monitoring.alerts.list</code></li>
</ul>
<p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring. dashboards. listEffectiveTags</code></p>
<p><code>monitoring. dashboards. listTagBindings</code></p>
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
<p><code>monitoring. notificationChannelDescriptors.*</code></p>
<ul>
<li><code>monitoring. notificationChannelDescriptors. get</code></li>
<li><code>monitoring. notificationChannelDescriptors. list</code></li>
</ul>
<p><code>monitoring. notificationChannels. get</code></p>
<p><code>monitoring. notificationChannels. list</code></p>
<p><code>monitoring.services.get</code></p>
<p><code>monitoring.services.list</code></p>
<p><code>monitoring.slos.get</code></p>
<p><code>monitoring.slos.list</code></p>
<p><code>monitoring.snoozes.get</code></p>
<p><code>monitoring.snoozes.list</code></p>
<p><code>monitoring.timeSeries.*</code></p>
<ul>
<li><code>monitoring.timeSeries.create</code></li>
<li><code>monitoring.timeSeries.list</code></li>
</ul>
<p><code>monitoring. uptimeCheckConfigs. get</code></p>
<p><code>monitoring. uptimeCheckConfigs. list</code></p>
<p><code>networkconnectivity. internalRanges.*</code></p>
<ul>
<li><code>networkconnectivity. internalRanges. create</code></li>
<li><code>networkconnectivity. internalRanges. delete</code></li>
<li><code>networkconnectivity. internalRanges. get</code></li>
<li><code>networkconnectivity. internalRanges. getIamPolicy</code></li>
<li><code>networkconnectivity. internalRanges. list</code></li>
<li><code>networkconnectivity. internalRanges. setIamPolicy</code></li>
<li><code>networkconnectivity. internalRanges. update</code></li>
</ul>
<p><code>networkconnectivity. locations.*</code></p>
<ul>
<li><code>networkconnectivity. locations. get</code></li>
<li><code>networkconnectivity. locations. list</code></li>
</ul>
<p><code>networkconnectivity. operations.*</code></p>
<ul>
<li><code>networkconnectivity. operations. cancel</code></li>
<li><code>networkconnectivity. operations. delete</code></li>
<li><code>networkconnectivity. operations. get</code></li>
<li><code>networkconnectivity. operations. list</code></li>
</ul>
<p><code>networkconnectivity. policyBasedRoutes.*</code></p>
<ul>
<li><code>networkconnectivity. policyBasedRoutes. create</code></li>
<li><code>networkconnectivity. policyBasedRoutes. delete</code></li>
<li><code>networkconnectivity. policyBasedRoutes. get</code></li>
<li><code>networkconnectivity. policyBasedRoutes. getIamPolicy</code></li>
<li><code>networkconnectivity. policyBasedRoutes. list</code></li>
<li><code>networkconnectivity. policyBasedRoutes. setIamPolicy</code></li>
</ul>
<p><code>networkconnectivity. regionalEndpoints.*</code></p>
<ul>
<li><code>networkconnectivity. regionalEndpoints. create</code></li>
<li><code>networkconnectivity. regionalEndpoints. delete</code></li>
<li><code>networkconnectivity. regionalEndpoints. get</code></li>
<li><code>networkconnectivity. regionalEndpoints. list</code></li>
</ul>
<p><code>networkconnectivity. serviceClasses.*</code></p>
<ul>
<li><code>networkconnectivity. serviceClasses. create</code></li>
<li><code>networkconnectivity. serviceClasses. delete</code></li>
<li><code>networkconnectivity. serviceClasses. get</code></li>
<li><code>networkconnectivity. serviceClasses. list</code></li>
<li><code>networkconnectivity. serviceClasses. update</code></li>
<li><code>networkconnectivity. serviceClasses. use</code></li>
</ul>
<p><code>networkconnectivity. serviceConnectionMaps.*</code></p>
<ul>
<li><code>networkconnectivity. serviceConnectionMaps. create</code></li>
<li><code>networkconnectivity. serviceConnectionMaps. delete</code></li>
<li><code>networkconnectivity. serviceConnectionMaps. get</code></li>
<li><code>networkconnectivity. serviceConnectionMaps. list</code></li>
<li><code>networkconnectivity. serviceConnectionMaps. update</code></li>
</ul>
<p><code>networkconnectivity. serviceConnectionPolicies.*</code></p>
<ul>
<li><code>networkconnectivity. serviceConnectionPolicies. create</code></li>
<li><code>networkconnectivity. serviceConnectionPolicies. delete</code></li>
<li><code>networkconnectivity. serviceConnectionPolicies. get</code></li>
<li><code>networkconnectivity. serviceConnectionPolicies. list</code></li>
<li><code>networkconnectivity. serviceConnectionPolicies. update</code></li>
</ul>
<p><code>networkmanagement. connectivitytests. get</code></p>
<p><code>networkmanagement. connectivitytests. list</code></p>
<p><code>networksecurity. addressGroups.*</code></p>
<ul>
<li><code>networksecurity. addressGroups. create</code></li>
<li><code>networksecurity. addressGroups. delete</code></li>
<li><code>networksecurity. addressGroups. get</code></li>
<li><code>networksecurity. addressGroups. getIamPolicy</code></li>
<li><code>networksecurity. addressGroups. list</code></li>
<li><code>networksecurity. addressGroups. setIamPolicy</code></li>
<li><code>networksecurity. addressGroups. update</code></li>
<li><code>networksecurity. addressGroups. use</code></li>
</ul>
<p><code>networksecurity. authorizationPolicies.*</code></p>
<ul>
<li><code>networksecurity. authorizationPolicies. create</code></li>
<li><code>networksecurity. authorizationPolicies. createTagBinding</code></li>
<li><code>networksecurity. authorizationPolicies. delete</code></li>
<li><code>networksecurity. authorizationPolicies. deleteTagBinding</code></li>
<li><code>networksecurity. authorizationPolicies. get</code></li>
<li><code>networksecurity. authorizationPolicies. getIamPolicy</code></li>
<li><code>networksecurity. authorizationPolicies. list</code></li>
<li><code>networksecurity. authorizationPolicies. listEffectiveTags</code></li>
<li><code>networksecurity. authorizationPolicies. listTagBindings</code></li>
<li><code>networksecurity. authorizationPolicies. setIamPolicy</code></li>
<li><code>networksecurity. authorizationPolicies. update</code></li>
<li><code>networksecurity. authorizationPolicies. use</code></li>
</ul>
<p><code>networksecurity. authzPolicies.*</code></p>
<ul>
<li><code>networksecurity. authzPolicies. create</code></li>
<li><code>networksecurity. authzPolicies. delete</code></li>
<li><code>networksecurity. authzPolicies. get</code></li>
<li><code>networksecurity. authzPolicies. getIamPolicy</code></li>
<li><code>networksecurity. authzPolicies. list</code></li>
<li><code>networksecurity. authzPolicies. setIamPolicy</code></li>
<li><code>networksecurity. authzPolicies. update</code></li>
</ul>
<p><code>networksecurity. backendAuthenticationConfigs.*</code></p>
<ul>
<li><code>networksecurity. backendAuthenticationConfigs. create</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. delete</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. get</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. list</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. update</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. use</code></li>
</ul>
<p><code>networksecurity. clientTlsPolicies.*</code></p>
<ul>
<li><code>networksecurity. clientTlsPolicies. create</code></li>
<li><code>networksecurity. clientTlsPolicies. createTagBinding</code></li>
<li><code>networksecurity. clientTlsPolicies. delete</code></li>
<li><code>networksecurity. clientTlsPolicies. deleteTagBinding</code></li>
<li><code>networksecurity. clientTlsPolicies. get</code></li>
<li><code>networksecurity. clientTlsPolicies. getIamPolicy</code></li>
<li><code>networksecurity. clientTlsPolicies. list</code></li>
<li><code>networksecurity. clientTlsPolicies. listEffectiveTags</code></li>
<li><code>networksecurity. clientTlsPolicies. listTagBindings</code></li>
<li><code>networksecurity. clientTlsPolicies. setIamPolicy</code></li>
<li><code>networksecurity. clientTlsPolicies. update</code></li>
<li><code>networksecurity. clientTlsPolicies. use</code></li>
</ul>
<p><code>networksecurity. firewallEndpointAssociations.*</code></p>
<ul>
<li><code>networksecurity. firewallEndpointAssociations. create</code></li>
<li><code>networksecurity. firewallEndpointAssociations. delete</code></li>
<li><code>networksecurity. firewallEndpointAssociations. get</code></li>
<li><code>networksecurity. firewallEndpointAssociations. list</code></li>
<li><code>networksecurity. firewallEndpointAssociations. update</code></li>
</ul>
<p><code>networksecurity. firewallEndpoints.*</code></p>
<ul>
<li><code>networksecurity. firewallEndpoints. create</code></li>
<li><code>networksecurity. firewallEndpoints. createVerdictChangeRequest</code></li>
<li><code>networksecurity. firewallEndpoints. delete</code></li>
<li><code>networksecurity. firewallEndpoints. get</code></li>
<li><code>networksecurity. firewallEndpoints. getVerdictChangeRequest</code></li>
<li><code>networksecurity. firewallEndpoints. getWildfireReport</code></li>
<li><code>networksecurity. firewallEndpoints. getWildfireSample</code></li>
<li><code>networksecurity. firewallEndpoints. list</code></li>
<li><code>networksecurity. firewallEndpoints. listVerdictChangeRequests</code></li>
<li><code>networksecurity. firewallEndpoints. submitVerdictChangeRequest</code></li>
<li><code>networksecurity. firewallEndpoints. update</code></li>
<li><code>networksecurity. firewallEndpoints. use</code></li>
<li><code>networksecurity. firewallEndpoints. useWildfire</code></li>
</ul>
<p><code>networksecurity. gatewaySecurityPolicies.*</code></p>
<ul>
<li><code>networksecurity. gatewaySecurityPolicies. create</code></li>
<li><code>networksecurity. gatewaySecurityPolicies. delete</code></li>
<li><code>networksecurity. gatewaySecurityPolicies. get</code></li>
<li><code>networksecurity. gatewaySecurityPolicies. list</code></li>
<li><code>networksecurity. gatewaySecurityPolicies. update</code></li>
<li><code>networksecurity. gatewaySecurityPolicies. use</code></li>
</ul>
<p><code>networksecurity. gatewaySecurityPolicyRules.*</code></p>
<ul>
<li><code>networksecurity. gatewaySecurityPolicyRules. create</code></li>
<li><code>networksecurity. gatewaySecurityPolicyRules. delete</code></li>
<li><code>networksecurity. gatewaySecurityPolicyRules. get</code></li>
<li><code>networksecurity. gatewaySecurityPolicyRules. list</code></li>
<li><code>networksecurity. gatewaySecurityPolicyRules. update</code></li>
<li><code>networksecurity. gatewaySecurityPolicyRules. use</code></li>
</ul>
<p><code>networksecurity.locations.*</code></p>
<ul>
<li><code>networksecurity.locations.get</code></li>
<li><code>networksecurity.locations.list</code></li>
</ul>
<p><code>networksecurity.operations.*</code></p>
<ul>
<li><code>networksecurity. operations. cancel</code></li>
<li><code>networksecurity. operations. delete</code></li>
<li><code>networksecurity.operations.get</code></li>
<li><code>networksecurity. operations. list</code></li>
</ul>
<p><code>networksecurity. sacAttachments.*</code></p>
<ul>
<li><code>networksecurity. sacAttachments. create</code></li>
<li><code>networksecurity. sacAttachments. delete</code></li>
<li><code>networksecurity. sacAttachments. get</code></li>
<li><code>networksecurity. sacAttachments. list</code></li>
</ul>
<p><code>networksecurity.sacRealms.*</code></p>
<ul>
<li><code>networksecurity. sacRealms. create</code></li>
<li><code>networksecurity. sacRealms. delete</code></li>
<li><code>networksecurity.sacRealms.get</code></li>
<li><code>networksecurity.sacRealms.list</code></li>
</ul>
<p><code>networksecurity. securityProfileGroups.*</code></p>
<ul>
<li><code>networksecurity. securityProfileGroups. create</code></li>
<li><code>networksecurity. securityProfileGroups. delete</code></li>
<li><code>networksecurity. securityProfileGroups. get</code></li>
<li><code>networksecurity. securityProfileGroups. list</code></li>
<li><code>networksecurity. securityProfileGroups. update</code></li>
<li><code>networksecurity. securityProfileGroups. use</code></li>
</ul>
<p><code>networksecurity. securityProfiles.*</code></p>
<ul>
<li><code>networksecurity. securityProfiles. create</code></li>
<li><code>networksecurity. securityProfiles. delete</code></li>
<li><code>networksecurity. securityProfiles. get</code></li>
<li><code>networksecurity. securityProfiles. list</code></li>
<li><code>networksecurity. securityProfiles. update</code></li>
<li><code>networksecurity. securityProfiles. use</code></li>
</ul>
<p><code>networksecurity. serverTlsPolicies.*</code></p>
<ul>
<li><code>networksecurity. serverTlsPolicies. create</code></li>
<li><code>networksecurity. serverTlsPolicies. createTagBinding</code></li>
<li><code>networksecurity. serverTlsPolicies. delete</code></li>
<li><code>networksecurity. serverTlsPolicies. deleteTagBinding</code></li>
<li><code>networksecurity. serverTlsPolicies. get</code></li>
<li><code>networksecurity. serverTlsPolicies. getIamPolicy</code></li>
<li><code>networksecurity. serverTlsPolicies. list</code></li>
<li><code>networksecurity. serverTlsPolicies. listEffectiveTags</code></li>
<li><code>networksecurity. serverTlsPolicies. listTagBindings</code></li>
<li><code>networksecurity. serverTlsPolicies. setIamPolicy</code></li>
<li><code>networksecurity. serverTlsPolicies. update</code></li>
<li><code>networksecurity. serverTlsPolicies. use</code></li>
</ul>
<p><code>networksecurity. tlsInspectionPolicies.*</code></p>
<ul>
<li><code>networksecurity. tlsInspectionPolicies. create</code></li>
<li><code>networksecurity. tlsInspectionPolicies. delete</code></li>
<li><code>networksecurity. tlsInspectionPolicies. get</code></li>
<li><code>networksecurity. tlsInspectionPolicies. list</code></li>
<li><code>networksecurity. tlsInspectionPolicies. update</code></li>
<li><code>networksecurity. tlsInspectionPolicies. use</code></li>
</ul>
<p><code>networksecurity.urlLists.*</code></p>
<ul>
<li><code>networksecurity. urlLists. create</code></li>
<li><code>networksecurity. urlLists. delete</code></li>
<li><code>networksecurity.urlLists.get</code></li>
<li><code>networksecurity.urlLists.list</code></li>
<li><code>networksecurity. urlLists. update</code></li>
<li><code>networksecurity.urlLists.use</code></li>
</ul>
<p><code>networkservices.*</code></p>
<ul>
<li><code>networkservices. agentGateways. create</code></li>
<li><code>networkservices. agentGateways. delete</code></li>
<li><code>networkservices. agentGateways. get</code></li>
<li><code>networkservices. agentGateways. list</code></li>
<li><code>networkservices. agentGateways. update</code></li>
<li><code>networkservices. agentGateways. use</code></li>
<li><code>networkservices. authzExtensions. create</code></li>
<li><code>networkservices. authzExtensions. delete</code></li>
<li><code>networkservices. authzExtensions. get</code></li>
<li><code>networkservices. authzExtensions. list</code></li>
<li><code>networkservices. authzExtensions. update</code></li>
<li><code>networkservices. authzExtensions. use</code></li>
<li><code>networkservices. endpointConfigSelectors. createTagBinding</code></li>
<li><code>networkservices. endpointConfigSelectors. deleteTagBinding</code></li>
<li><code>networkservices. endpointConfigSelectors. listEffectiveTags</code></li>
<li><code>networkservices. endpointConfigSelectors. listTagBindings</code></li>
<li><code>networkservices. endpointPolicies. create</code></li>
<li><code>networkservices. endpointPolicies. delete</code></li>
<li><code>networkservices. endpointPolicies. get</code></li>
<li><code>networkservices. endpointPolicies. list</code></li>
<li><code>networkservices. endpointPolicies. update</code></li>
<li><code>networkservices. gateways. create</code></li>
<li><code>networkservices. gateways. createTagBinding</code></li>
<li><code>networkservices. gateways. delete</code></li>
<li><code>networkservices. gateways. deleteTagBinding</code></li>
<li><code>networkservices.gateways.get</code></li>
<li><code>networkservices.gateways.list</code></li>
<li><code>networkservices. gateways. listEffectiveTags</code></li>
<li><code>networkservices. gateways. listTagBindings</code></li>
<li><code>networkservices. gateways. update</code></li>
<li><code>networkservices.gateways.use</code></li>
<li><code>networkservices. googleTagGatewayPolicies. create</code></li>
<li><code>networkservices. googleTagGatewayPolicies. delete</code></li>
<li><code>networkservices. googleTagGatewayPolicies. get</code></li>
<li><code>networkservices. googleTagGatewayPolicies. list</code></li>
<li><code>networkservices. googleTagGatewayPolicies. update</code></li>
<li><code>networkservices. grpcRoutes. create</code></li>
<li><code>networkservices. grpcRoutes. delete</code></li>
<li><code>networkservices.grpcRoutes.get</code></li>
<li><code>networkservices. grpcRoutes. list</code></li>
<li><code>networkservices. grpcRoutes. update</code></li>
<li><code>networkservices. httpFilters. create</code></li>
<li><code>networkservices. httpFilters. createTagBinding</code></li>
<li><code>networkservices. httpFilters. delete</code></li>
<li><code>networkservices. httpFilters. deleteTagBinding</code></li>
<li><code>networkservices. httpFilters. get</code></li>
<li><code>networkservices. httpFilters. list</code></li>
<li><code>networkservices. httpFilters. listEffectiveTags</code></li>
<li><code>networkservices. httpFilters. listTagBindings</code></li>
<li><code>networkservices. httpFilters. update</code></li>
<li><code>networkservices. httpRoutes. create</code></li>
<li><code>networkservices. httpRoutes. delete</code></li>
<li><code>networkservices.httpRoutes.get</code></li>
<li><code>networkservices. httpRoutes. list</code></li>
<li><code>networkservices. httpRoutes. update</code></li>
<li><code>networkservices. httpfilters. create</code></li>
<li><code>networkservices. httpfilters. delete</code></li>
<li><code>networkservices. httpfilters. get</code></li>
<li><code>networkservices. httpfilters. getIamPolicy</code></li>
<li><code>networkservices. httpfilters. list</code></li>
<li><code>networkservices. httpfilters. setIamPolicy</code></li>
<li><code>networkservices. httpfilters. update</code></li>
<li><code>networkservices. httpfilters. use</code></li>
<li><code>networkservices. lbEdgeExtensions. create</code></li>
<li><code>networkservices. lbEdgeExtensions. delete</code></li>
<li><code>networkservices. lbEdgeExtensions. get</code></li>
<li><code>networkservices. lbEdgeExtensions. list</code></li>
<li><code>networkservices. lbEdgeExtensions. update</code></li>
<li><code>networkservices. lbRouteExtensions. create</code></li>
<li><code>networkservices. lbRouteExtensions. delete</code></li>
<li><code>networkservices. lbRouteExtensions. get</code></li>
<li><code>networkservices. lbRouteExtensions. list</code></li>
<li><code>networkservices. lbRouteExtensions. update</code></li>
<li><code>networkservices. lbTcpExtensions. createForNetwork</code></li>
<li><code>networkservices. lbTcpExtensions. deleteForNetwork</code></li>
<li><code>networkservices. lbTcpExtensions. getForNetwork</code></li>
<li><code>networkservices. lbTcpExtensions. listForNetwork</code></li>
<li><code>networkservices. lbTcpExtensions. updateForNetwork</code></li>
<li><code>networkservices. lbTrafficExtensions. create</code></li>
<li><code>networkservices. lbTrafficExtensions. delete</code></li>
<li><code>networkservices. lbTrafficExtensions. get</code></li>
<li><code>networkservices. lbTrafficExtensions. list</code></li>
<li><code>networkservices. lbTrafficExtensions. update</code></li>
<li><code>networkservices.locations.get</code></li>
<li><code>networkservices.locations.list</code></li>
<li><code>networkservices.meshes.create</code></li>
<li><code>networkservices. meshes. createTagBinding</code></li>
<li><code>networkservices.meshes.delete</code></li>
<li><code>networkservices. meshes. deleteTagBinding</code></li>
<li><code>networkservices.meshes.get</code></li>
<li><code>networkservices.meshes.list</code></li>
<li><code>networkservices. meshes. listEffectiveTags</code></li>
<li><code>networkservices. meshes. listTagBindings</code></li>
<li><code>networkservices.meshes.update</code></li>
<li><code>networkservices.meshes.use</code></li>
<li><code>networkservices. operations. cancel</code></li>
<li><code>networkservices. operations. delete</code></li>
<li><code>networkservices.operations.get</code></li>
<li><code>networkservices. operations. list</code></li>
<li><code>networkservices. route_views. get</code></li>
<li><code>networkservices. route_views. list</code></li>
<li><code>networkservices. serviceBindings. create</code></li>
<li><code>networkservices. serviceBindings. delete</code></li>
<li><code>networkservices. serviceBindings. get</code></li>
<li><code>networkservices. serviceBindings. list</code></li>
<li><code>networkservices. serviceBindings. update</code></li>
<li><code>networkservices. serviceLbPolicies. create</code></li>
<li><code>networkservices. serviceLbPolicies. delete</code></li>
<li><code>networkservices. serviceLbPolicies. get</code></li>
<li><code>networkservices. serviceLbPolicies. list</code></li>
<li><code>networkservices. serviceLbPolicies. update</code></li>
<li><code>networkservices. swpSecurityExtensions. create</code></li>
<li><code>networkservices. swpSecurityExtensions. delete</code></li>
<li><code>networkservices. swpSecurityExtensions. get</code></li>
<li><code>networkservices. swpSecurityExtensions. list</code></li>
<li><code>networkservices. swpSecurityExtensions. update</code></li>
<li><code>networkservices. tcpRoutes. create</code></li>
<li><code>networkservices. tcpRoutes. delete</code></li>
<li><code>networkservices.tcpRoutes.get</code></li>
<li><code>networkservices.tcpRoutes.list</code></li>
<li><code>networkservices. tcpRoutes. update</code></li>
<li><code>networkservices. tlsRoutes. create</code></li>
<li><code>networkservices. tlsRoutes. delete</code></li>
<li><code>networkservices.tlsRoutes.get</code></li>
<li><code>networkservices.tlsRoutes.list</code></li>
<li><code>networkservices. tlsRoutes. update</code></li>
<li><code>networkservices. wasmPlugins. create</code></li>
<li><code>networkservices. wasmPlugins. delete</code></li>
<li><code>networkservices. wasmPlugins. get</code></li>
<li><code>networkservices. wasmPlugins. list</code></li>
<li><code>networkservices. wasmPlugins. update</code></li>
<li><code>networkservices. wasmPlugins. use</code></li>
</ul>
<p><code>observability.scopes.get</code></p>
<p><code>opsconfigmonitoring. resourceMetadata. list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>pubsub. messageTransforms. validate</code></p>
<p><code>pubsub.schemas.*</code></p>
<ul>
<li><code>pubsub.schemas.attach</code></li>
<li><code>pubsub.schemas.commit</code></li>
<li><code>pubsub.schemas.create</code></li>
<li><code>pubsub.schemas.delete</code></li>
<li><code>pubsub.schemas.get</code></li>
<li><code>pubsub.schemas.getIamPolicy</code></li>
<li><code>pubsub.schemas.list</code></li>
<li><code>pubsub.schemas.listRevisions</code></li>
<li><code>pubsub.schemas.rollback</code></li>
<li><code>pubsub.schemas.setIamPolicy</code></li>
<li><code>pubsub.schemas.validate</code></li>
</ul>
<p><code>pubsub.snapshots.create</code></p>
<p><code>pubsub.snapshots.delete</code></p>
<p><code>pubsub.snapshots.get</code></p>
<p><code>pubsub.snapshots.getIamPolicy</code></p>
<p><code>pubsub.snapshots.list</code></p>
<p><code>pubsub. snapshots. listEffectiveTags</code></p>
<p><code>pubsub. snapshots. listTagBindings</code></p>
<p><code>pubsub.snapshots.seek</code></p>
<p><code>pubsub.snapshots.setIamPolicy</code></p>
<p><code>pubsub.snapshots.update</code></p>
<p><code>pubsub.subscriptions.consume</code></p>
<p><code>pubsub.subscriptions.create</code></p>
<p><code>pubsub.subscriptions.delete</code></p>
<p><code>pubsub.subscriptions.get</code></p>
<p><code>pubsub. subscriptions. getIamPolicy</code></p>
<p><code>pubsub.subscriptions.list</code></p>
<p><code>pubsub. subscriptions. listEffectiveTags</code></p>
<p><code>pubsub. subscriptions. listTagBindings</code></p>
<p><code>pubsub. subscriptions. setIamPolicy</code></p>
<p><code>pubsub.subscriptions.update</code></p>
<p><code>pubsub. topics. attachSubscription</code></p>
<p><code>pubsub.topics.create</code></p>
<p><code>pubsub.topics.delete</code></p>
<p><code>pubsub. topics. detachSubscription</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.getIamPolicy</code></p>
<p><code>pubsub.topics.list</code></p>
<p><code>pubsub. topics. listEffectiveTags</code></p>
<p><code>pubsub.topics.listTagBindings</code></p>
<p><code>pubsub.topics.publish</code></p>
<p><code>pubsub.topics.setIamPolicy</code></p>
<p><code>pubsub.topics.update</code></p>
<p><code>pubsub.topics.updateTag</code></p>
<p><code>recommender. appengineVersionCostInsights.*</code></p>
<ul>
<li><code>recommender. appengineVersionCostInsights. get</code></li>
<li><code>recommender. appengineVersionCostInsights. list</code></li>
<li><code>recommender. appengineVersionCostInsights. update</code></li>
</ul>
<p><code>recommender. appengineVersionCostRecommendations.*</code></p>
<ul>
<li><code>recommender. appengineVersionCostRecommendations. get</code></li>
<li><code>recommender. appengineVersionCostRecommendations. list</code></li>
<li><code>recommender. appengineVersionCostRecommendations. update</code></li>
</ul>
<p><code>recommender. cloudsqlIdleInstanceRecommendations.*</code></p>
<ul>
<li><code>recommender. cloudsqlIdleInstanceRecommendations. get</code></li>
<li><code>recommender. cloudsqlIdleInstanceRecommendations. list</code></li>
<li><code>recommender. cloudsqlIdleInstanceRecommendations. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstanceActivityInsights.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstanceActivityInsights. get</code></li>
<li><code>recommender. cloudsqlInstanceActivityInsights. list</code></li>
<li><code>recommender. cloudsqlInstanceActivityInsights. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstanceCpuUsageInsights.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstanceCpuUsageInsights. get</code></li>
<li><code>recommender. cloudsqlInstanceCpuUsageInsights. list</code></li>
<li><code>recommender. cloudsqlInstanceCpuUsageInsights. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstanceDiskUsageTrendInsights.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstanceDiskUsageTrendInsights. get</code></li>
<li><code>recommender. cloudsqlInstanceDiskUsageTrendInsights. list</code></li>
<li><code>recommender. cloudsqlInstanceDiskUsageTrendInsights. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstanceMemoryUsageInsights.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstanceMemoryUsageInsights. get</code></li>
<li><code>recommender. cloudsqlInstanceMemoryUsageInsights. list</code></li>
<li><code>recommender. cloudsqlInstanceMemoryUsageInsights. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstanceOomProbabilityInsights.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstanceOomProbabilityInsights. get</code></li>
<li><code>recommender. cloudsqlInstanceOomProbabilityInsights. list</code></li>
<li><code>recommender. cloudsqlInstanceOomProbabilityInsights. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstanceOutOfDiskRecommendations.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstanceOutOfDiskRecommendations. get</code></li>
<li><code>recommender. cloudsqlInstanceOutOfDiskRecommendations. list</code></li>
<li><code>recommender. cloudsqlInstanceOutOfDiskRecommendations. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstancePerformanceInsights.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstancePerformanceInsights. get</code></li>
<li><code>recommender. cloudsqlInstancePerformanceInsights. list</code></li>
<li><code>recommender. cloudsqlInstancePerformanceInsights. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstancePerformanceRecommendations.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstancePerformanceRecommendations. get</code></li>
<li><code>recommender. cloudsqlInstancePerformanceRecommendations. list</code></li>
<li><code>recommender. cloudsqlInstancePerformanceRecommendations. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstanceReliabilityInsights.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstanceReliabilityInsights. get</code></li>
<li><code>recommender. cloudsqlInstanceReliabilityInsights. list</code></li>
<li><code>recommender. cloudsqlInstanceReliabilityInsights. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstanceReliabilityRecommendations.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstanceReliabilityRecommendations. get</code></li>
<li><code>recommender. cloudsqlInstanceReliabilityRecommendations. list</code></li>
<li><code>recommender. cloudsqlInstanceReliabilityRecommendations. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstanceSecurityInsights.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstanceSecurityInsights. get</code></li>
<li><code>recommender. cloudsqlInstanceSecurityInsights. list</code></li>
<li><code>recommender. cloudsqlInstanceSecurityInsights. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstanceSecurityRecommendations.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstanceSecurityRecommendations. get</code></li>
<li><code>recommender. cloudsqlInstanceSecurityRecommendations. list</code></li>
<li><code>recommender. cloudsqlInstanceSecurityRecommendations. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstanceUnderprovisionedCpuUsageInsights.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstanceUnderprovisionedCpuUsageInsights. get</code></li>
<li><code>recommender. cloudsqlInstanceUnderprovisionedCpuUsageInsights. list</code></li>
<li><code>recommender. cloudsqlInstanceUnderprovisionedCpuUsageInsights. update</code></li>
</ul>
<p><code>recommender. cloudsqlInstanceUnderprovisionedMemoryUsageInsights.*</code></p>
<ul>
<li><code>recommender. cloudsqlInstanceUnderprovisionedMemoryUsageInsights. get</code></li>
<li><code>recommender. cloudsqlInstanceUnderprovisionedMemoryUsageInsights. list</code></li>
<li><code>recommender. cloudsqlInstanceUnderprovisionedMemoryUsageInsights. update</code></li>
</ul>
<p><code>recommender. cloudsqlOverprovisionedInstanceRecommendations.*</code></p>
<ul>
<li><code>recommender. cloudsqlOverprovisionedInstanceRecommendations. get</code></li>
<li><code>recommender. cloudsqlOverprovisionedInstanceRecommendations. list</code></li>
<li><code>recommender. cloudsqlOverprovisionedInstanceRecommendations. update</code></li>
</ul>
<p><code>recommender. cloudsqlUnderProvisionedInstanceRecommendations.*</code></p>
<ul>
<li><code>recommender. cloudsqlUnderProvisionedInstanceRecommendations. get</code></li>
<li><code>recommender. cloudsqlUnderProvisionedInstanceRecommendations. list</code></li>
<li><code>recommender. cloudsqlUnderProvisionedInstanceRecommendations. update</code></li>
</ul>
<p><code>recommender. containerDiagnosisInsights.*</code></p>
<ul>
<li><code>recommender. containerDiagnosisInsights. get</code></li>
<li><code>recommender. containerDiagnosisInsights. list</code></li>
<li><code>recommender. containerDiagnosisInsights. update</code></li>
</ul>
<p><code>recommender. containerDiagnosisRecommendations.*</code></p>
<ul>
<li><code>recommender. containerDiagnosisRecommendations. get</code></li>
<li><code>recommender. containerDiagnosisRecommendations. list</code></li>
<li><code>recommender. containerDiagnosisRecommendations. update</code></li>
</ul>
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
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>recommender. networkAnalyzerGkeConnectivityInsights.*</code></p>
<ul>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. get</code></li>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. list</code></li>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. update</code></li>
</ul>
<p><code>recommender. networkAnalyzerGkeIpAddressInsights.*</code></p>
<ul>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. get</code></li>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. list</code></li>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. update</code></li>
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
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>servicedirectory. namespaces. create</code></p>
<p><code>servicedirectory. namespaces. delete</code></p>
<p><code>servicedirectory. services. create</code></p>
<p><code>servicedirectory. services. delete</code></p>
<p><code>servicenetworking. operations. get</code></p>
<p><code>servicenetworking. services. addPeering</code></p>
<p><code>servicenetworking. services. createPeeredDnsDomain</code></p>
<p><code>servicenetworking. services. deleteConnection</code></p>
<p><code>servicenetworking. services. deletePeeredDnsDomain</code></p>
<p><code>servicenetworking. services. disableVpcServiceControls</code></p>
<p><code>servicenetworking. services. enableVpcServiceControls</code></p>
<p><code>servicenetworking.services.get</code></p>
<p><code>servicenetworking. services. getVpcServiceControls</code></p>
<p><code>servicenetworking. services. listPeeredDnsDomains</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
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
</ul>
<p><code>trafficdirector.*</code></p>
<ul>
<li><code>trafficdirector. networks. getConfigs</code></li>
<li><code>trafficdirector. networks. reportMetrics</code></li>
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
<td><code>composer.dags.execute</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer.dags.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>composer.dags.getSourceCode</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer.dags.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>composer.environments.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer. environments. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>composer.environments.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer. environments. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>composer. environments. executeAirflowCommand</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer.environments.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>composer.environments.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer. environments. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>composer. environments. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer.environments.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>composer.imageversions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>composer.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>composer. userworkloadsconfigmaps. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer. userworkloadsconfigmaps. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>composer. userworkloadsconfigmaps. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer. userworkloadsconfigmaps. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>composer. userworkloadsconfigmaps. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer. userworkloadssecrets. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>composer. userworkloadssecrets. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer. userworkloadssecrets. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>composer. userworkloadssecrets. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>composer. userworkloadssecrets. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p></td>
</tr>
</tbody>
</table>
