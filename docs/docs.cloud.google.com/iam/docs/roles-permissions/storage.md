---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/storage
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/storage
title: Cloud Storage roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Storage. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Storage roles

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
<td>Storage Admin
<p>( <code>roles/ storage.admin</code> )</p>
<p>Grants full control of objects and buckets.</p>
<p>When applied to an individual <strong>bucket</strong> , control applies only to the specified bucket and objects within the bucket.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring.groups.get</code></p>
<p><code>monitoring.groups.list</code></p>
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
<tr class="even">
<td>Storage Bucket Viewer <sup>Beta</sup>
<p>( <code>roles/ storage.bucketViewer</code> )</p>
<p>Grants permission to view buckets and their metadata, excluding IAM policies.</p></td>
<td><p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.list</code></p></td>
</tr>
<tr class="odd">
<td>Storage Editor
<p>( <code>roles/ storage.editor</code> )</p>
<p>Editor role for storage</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.delete</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage. buckets. listEffectiveTags</code></p>
<p><code>storage. buckets. listTagBindings</code></p>
<p><code>storage. buckets. viewIntelligenceDetails</code></p>
<p><code>storage. buckets. viewSecurityIntelligenceDetails</code></p>
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
<p><code>storage.hmacKeys.*</code></p>
<ul>
<li><code>storage.hmacKeys.create</code></li>
<li><code>storage.hmacKeys.delete</code></li>
<li><code>storage.hmacKeys.get</code></li>
<li><code>storage.hmacKeys.list</code></li>
<li><code>storage.hmacKeys.update</code></li>
</ul>
<p><code>storage. intelligenceConfigs. get</code></p></td>
</tr>
<tr class="even">
<td>Storage Folder Admin
<p>( <code>roles/ storage.folderAdmin</code> )</p>
<p>Grants full control over folders and objects, including listing, creating, viewing, and deleting objects.</p></td>
<td><p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
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
</ul></td>
</tr>
<tr class="odd">
<td>Storage Legacy Bucket Owner
<p>( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p>Grants permission to create, overwrite, and delete objects; list objects in a bucket and read object metadata, excluding allow policies, when listing; and read and edit bucket metadata, including allow policies.</p>
<p>Use of this role is also reflected in the bucket's ACLs. For more information, see <a href="https://docs.cloud.google.com/storage/docs/access-control/iam#acls">IAM relation to ACLs</a> .</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code>storage.anywhereCaches.*</code></p>
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
<p><code>storage. buckets. createTagBinding</code></p>
<p><code>storage. buckets. deleteTagBinding</code></p>
<p><code>storage. buckets. enableObjectRetention</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.getIpFilter</code></p>
<p><code>storage. buckets. listEffectiveTags</code></p>
<p><code>storage. buckets. listTagBindings</code></p>
<p><code>storage.buckets.relocate</code></p>
<p><code>storage.buckets.restore</code></p>
<p><code>storage.buckets.setIamPolicy</code></p>
<p><code>storage.buckets.setIpFilter</code></p>
<p><code>storage.buckets.update</code></p>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
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
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.createContext</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.deleteContext</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.restore</code></p>
<p><code>storage.objects.setRetention</code></p>
<p><code>storage.objects.updateContext</code></p></td>
</tr>
<tr class="even">
<td>Storage Legacy Bucket Reader
<p>( <code>roles/ storage.legacyBucketReader</code> )</p>
<p>Grants permission to list a bucket's contents and read bucket metadata, excluding allow policies. Also grants permission to read object metadata, excluding allow policies, when listing objects.</p>
<p>Use of this role is also reflected in the bucket's ACLs. For more information, see <a href="https://docs.cloud.google.com/storage/docs/access-control/iam#acls">IAM relation to ACLs</a> .</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code>storage.buckets.get</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.multipartUploads.list</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td>Storage Legacy Bucket Writer
<p>( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p>Grants permission to create, overwrite, and delete objects; list objects in a bucket and read object metadata, excluding allow policies, when listing; and read bucket metadata, excluding allow policies.</p>
<p>Use of this role is also reflected in the bucket's ACLs. For more information, see <a href="https://docs.cloud.google.com/storage/docs/access-control/iam#acls">IAM relation to ACLs</a> .</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code>storage.buckets.get</code></p>
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
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.createContext</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.restore</code></p>
<p><code>storage.objects.setRetention</code></p></td>
</tr>
<tr class="even">
<td>Storage Legacy Object Owner
<p>( <code>roles/ storage.legacyObjectOwner</code> )</p>
<p>Grants permission to view and edit objects and their metadata, including ACLs.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code>storage.objects.createContext</code></p>
<p><code>storage.objects.deleteContext</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.getIamPolicy</code></p>
<p><code>storage. objects. overrideUnlockedRetention</code></p>
<p><code>storage.objects.setIamPolicy</code></p>
<p><code>storage.objects.setRetention</code></p>
<p><code>storage.objects.update</code></p>
<p><code>storage.objects.updateContext</code></p></td>
</tr>
<tr class="odd">
<td>Storage Legacy Object Reader
<p>( <code>roles/ storage.legacyObjectReader</code> )</p>
<p>Grants permission to view objects and their metadata, excluding ACLs.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code>storage.objects.get</code></p></td>
</tr>
<tr class="even">
<td>Storage Object Admin
<p>( <code>roles/ storage.objectAdmin</code> )</p>
<p>Grants full control of objects, including listing, creating, viewing, and deleting objects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code>monitoring.timeSeries.create</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
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
<td>Storage Object Creator
<p>( <code>roles/ storage.objectCreator</code> )</p>
<p>Allows users to create objects. Does not give permission to view, delete, or overwrite objects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.folders.create</code></p>
<p><code>storage.managedFolders.create</code></p>
<p><code>storage.multipartUploads.abort</code></p>
<p><code>storage. multipartUploads. create</code></p>
<p><code>storage. multipartUploads. listParts</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.createContext</code></p></td>
</tr>
<tr class="even">
<td>Storage Object User
<p>( <code>roles/ storage.objectUser</code> )</p>
<p>Access to create, read, update and delete objects and multipart uploads in GCS.</p></td>
<td><p><code>monitoring.timeSeries.create</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
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
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.createContext</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.deleteContext</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.move</code></p>
<p><code>storage.objects.restore</code></p>
<p><code>storage.objects.update</code></p>
<p><code>storage.objects.updateContext</code></p></td>
</tr>
<tr class="odd">
<td>Storage Object Viewer
<p>( <code>roles/ storage.objectViewer</code> )</p>
<p>Grants access to view objects and their metadata, excluding ACLs. Can also list the objects in a bucket.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td>Storage Viewer
<p>( <code>roles/ storage.viewer</code> )</p>
<p>Viewer role for storage</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage. buckets. listEffectiveTags</code></p>
<p><code>storage. buckets. listTagBindings</code></p>
<p><code>storage. buckets. viewIntelligenceDetails</code></p>
<p><code>storage. buckets. viewSecurityIntelligenceDetails</code></p>
<p><code>storage.featureConfigs.get</code></p>
<p><code>storage.featureConfigs.list</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.hmacKeys.get</code></p>
<p><code>storage.hmacKeys.list</code></p>
<p><code>storage. intelligenceConfigs. get</code></p></td>
</tr>
<tr class="odd">
<td>Storage Annotation Generator Service <sup>Beta</sup>
<p>( <code>roles/ storage.annotationGeneratorService</code> )</p>
<p>Grants all permissions needed to generate annotations for objects in a bucket.</p></td>
<td><p><code>storage.objects.createContext</code></p>
<p><code>storage.objects.deleteContext</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p>
<p><code>storage.objects.updateContext</code></p></td>
</tr>
<tr class="even">
<td>Storage Express Mode Service Input <sup>Beta</sup>
<p>( <code>roles/ storage.expressModeServiceInput</code> )</p>
<p>Grants permission to Express Mode service accounts at a managed folder so they can create objects but not read them on input folders.</p></td>
<td><p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p></td>
</tr>
<tr class="odd">
<td>Storage Express Mode Service Output <sup>Beta</sup>
<p>( <code>roles/ storage.expressModeServiceOutput</code> )</p>
<p>Grants permission to Express Mode service accounts at a managed folder so they can read objects but not write them on output folders.</p></td>
<td><p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td>Storage Express Mode User Access <sup>Beta</sup>
<p>( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p>Grants permission to Express Mode accounts at the project level so they can read, list, create and delete any object in any of their buckets in Express Mode.</p></td>
<td><p><code>orgpolicy.policy.get</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.multipartUploads.*</code></p>
<ul>
<li><code>storage.multipartUploads.abort</code></li>
<li><code>storage. multipartUploads. create</code></li>
<li><code>storage.multipartUploads.list</code></li>
<li><code>storage. multipartUploads. listParts</code></li>
</ul>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.restore</code></p>
<p><code>storage.objects.update</code></p></td>
</tr>
<tr class="odd">
<td>Storage HMAC Key Admin
<p>( <code>roles/ storage.hmacKeyAdmin</code> )</p>
<p>Full control of Cloud Storage HMAC keys.</p></td>
<td><p><code>firebase.projects.get</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.hmacKeys.*</code></p>
<ul>
<li><code>storage.hmacKeys.create</code></li>
<li><code>storage.hmacKeys.delete</code></li>
<li><code>storage.hmacKeys.get</code></li>
<li><code>storage.hmacKeys.list</code></li>
<li><code>storage.hmacKeys.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Storage Insights Collector Service
<p>( <code>roles/ storage.insightsCollectorService</code> )</p>
<p>Read-only access to Cloud Storage Inventory metadata for Storage Insights.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage. buckets. getObjectInsights</code></p></td>
</tr>
</tbody>
</table>

## Cloud Storage permissions

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
<td><code>storage.anywhereCaches.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.anywhereCaches.disable</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.anywhereCaches.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.anywhereCaches.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.anywhereCaches.pause</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.anywhereCaches.resume</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.anywhereCaches.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage. bucketOperations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.bucketOperations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.bucketOperations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.buckets.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudStorageOperator">Backup and DR Cloud Storage Operator</a> ( <code>roles/ backupdr.cloudStorageOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code>roles/ cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code>roles/ config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal#aiedgeportal.serviceAgent">AI Edge Portal Service Agent</a> ( <code>roles/ aiedgeportal.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code>roles/ aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code>roles/ aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a> ( <code>roles/ cloudasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a> ( <code>roles/ clouddeploy.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.serviceAgent">Device Run Service Agent</a> ( <code>roles/ devicerun.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code>roles/ runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code>roles/ spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code>roles/ stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage. buckets. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.buckets.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code>roles/ cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code>roles/ config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code>roles/ aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code>roles/ aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code>roles/ runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage. buckets. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage. buckets. enableObjectRetention</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.buckets.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.bucketViewer">Storage Bucket Viewer</a> ( <code>roles/ storage.bucketViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code>roles/ storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudStorageOperator">Backup and DR Cloud Storage Operator</a> ( <code>roles/ backupdr.cloudStorageOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code>roles/ cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code>roles/ config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataOwner">Dataplex Storage Data Owner</a> ( <code>roles/ dataplex.storageDataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataReader">Dataplex Storage Data Reader</a> ( <code>roles/ dataplex.storageDataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code>roles/ dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.insightsCollectorService">Storage Insights Collector Service</a> ( <code>roles/ storage.insightsCollectorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal#aiedgeportal.serviceAgent">AI Edge Portal Service Agent</a> ( <code>roles/ aiedgeportal.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code>roles/ aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code>roles/ aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code>roles/ automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code>roles/ chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a> ( <code>roles/ cloudasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a> ( <code>roles/ clouddeploy.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a> ( <code>roles/ cloudoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code>roles/ cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code>roles/ contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.discoveryServiceAgent">Dataplex Discovery Service Agent</a> ( <code>roles/ dataplex.discoveryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code>roles/ datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.managedStorageServiceAgent">Data Studio Managed Storage Service Agent</a> ( <code>roles/ datastudio.managedStorageServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.serviceAgent">Device Run Service Agent</a> ( <code>roles/ devicerun.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code>roles/ documentaicore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code>roles/ eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code>roles/ firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasetelemetry#firebasetelemetry.serviceAgent">Firebase Telemetry Service Agent</a> ( <code>roles/ firebasetelemetry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#firestore.serviceAgent">Firestore Service Agent</a> ( <code>roles/ firestore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/generativelanguage#generativelanguage.serviceAgent">Generative Language Service Agent</a> ( <code>roles/ generativelanguage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kuberun#kuberun.eventsControlPlaneServiceAgent">KubeRun Events Control Plane Service Agent</a> ( <code>roles/ kuberun.eventsControlPlaneServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.serviceAgent">Route Optimization Service Agent</a> ( <code>roles/ routeoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code>roles/ runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityResponseServiceAgent">Google Cloud Security Response Service Agent</a> ( <code>roles/ securitycenter.securityResponseServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code>roles/ spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a> ( <code>roles/ speech.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code>roles/ stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code>roles/ vectorsearch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.buckets.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code>roles/ chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a> ( <code>roles/ cloudasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code>roles/ firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.buckets.getIpFilter</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage. buckets. getObjectInsights</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.insightsCollectorService">Storage Insights Collector Service</a> ( <code>roles/ storage.insightsCollectorService</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.buckets.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.bucketViewer">Storage Bucket Viewer</a> ( <code>roles/ storage.bucketViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code>roles/ cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code>roles/ config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal#aiedgeportal.serviceAgent">AI Edge Portal Service Agent</a> ( <code>roles/ aiedgeportal.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code>roles/ aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code>roles/ aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code>roles/ chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code>roles/ contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.serviceAgent">Device Run Service Agent</a> ( <code>roles/ devicerun.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code>roles/ spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a> ( <code>roles/ speech.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage. buckets. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage. buckets. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.buckets.relocate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.buckets.restore</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.buckets.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.buckets.setIpFilter</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.buckets.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code>roles/ cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code>roles/ config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code>roles/ aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code>roles/ aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code>roles/ chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code>roles/ eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kuberun#kuberun.eventsControlPlaneServiceAgent">KubeRun Events Control Plane Service Agent</a> ( <code>roles/ kuberun.eventsControlPlaneServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityResponseServiceAgent">Google Cloud Security Response Service Agent</a> ( <code>roles/ securitycenter.securityResponseServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage. buckets. viewIntelligenceDetails</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage. buckets. viewSecurityIntelligenceDetails</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.featureConfigs.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.featureConfigs.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.featureConfigs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.featureConfigs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.featureConfigs.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.folders.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code>roles/ storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.folders.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code>roles/ datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.folders.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code>roles/ storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code>roles/ storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.folders.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code>roles/ storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code>roles/ storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.folders.rename</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.hmacKeys.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code>roles/ storage.hmacKeyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.hmacKeys.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code>roles/ storage.hmacKeyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>storage.hmacKeys.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code>roles/ storage.hmacKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>storage.hmacKeys.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code>roles/ storage.hmacKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>storage.hmacKeys.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code>roles/ storage.hmacKeyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>storage. intelligenceConfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage. intelligenceConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.managedFolders.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code>roles/ storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.managedFolders.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.managedFolders.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code>roles/ storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code>roles/ storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage. managedFolders. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.managedFolders.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code>roles/ storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code>roles/ storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage. managedFolders. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.managedFolders.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.multipartUploads.abort</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code>roles/ storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage. multipartUploads. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code>roles/ storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.multipartUploads.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code>roles/ storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage. multipartUploads. listParts</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code>roles/ storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.objects.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code>roles/ firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code>roles/ storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudStorageOperator">Backup and DR Cloud Storage Operator</a> ( <code>roles/ backupdr.cloudStorageOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.worker">Task Worker</a> ( <code>roles/ bigquerymigration.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.jobRunner">Cloud Deploy Runner</a> ( <code>roles/ clouddeploy.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.storageaccess">Velostrata Storage Access</a> ( <code>roles/ cloudmigration.storageaccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code>roles/ config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataOwner">Dataplex Storage Data Owner</a> ( <code>roles/ dataplex.storageDataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataWriter">Dataplex Storage Data Writer</a> ( <code>roles/ dataplex.storageDataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceInput">Storage Express Mode Service Input</a> ( <code>roles/ storage.expressModeServiceInput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal#aiedgeportal.serviceAgent">AI Edge Portal Service Agent</a> ( <code>roles/ aiedgeportal.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentSandboxServiceAgent">Vertex AI Agent Sandbox Service Agent</a> ( <code>roles/ aiplatform.agentSandboxServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code>roles/ aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code>roles/ aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code>roles/ automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a> ( <code>roles/ cloudasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a> ( <code>roles/ cloudoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code>roles/ cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code>roles/ contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code>roles/ datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.managedStorageServiceAgent">Data Studio Managed Storage Service Agent</a> ( <code>roles/ datastudio.managedStorageServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.serviceAgent">Device Run Service Agent</a> ( <code>roles/ devicerun.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code>roles/ documentaicore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code>roles/ firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#firestore.serviceAgent">Firestore Service Agent</a> ( <code>roles/ firestore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.serviceAgent">Live Stream Service Agent</a> ( <code>roles/ livestream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mediaasset#mediaasset.serviceAgent">Media Asset Service Agent</a> ( <code>roles/ mediaasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.serviceAgent">Route Optimization Service Agent</a> ( <code>roles/ routeoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code>roles/ runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code>roles/ spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a> ( <code>roles/ speech.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code>roles/ stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.serviceAgent">Transcoder Service Agent</a> ( <code>roles/ transcoder.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code>roles/ vectorsearch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.objects.createContext</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code>roles/ storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code>roles/ storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.annotationGeneratorService">Storage Annotation Generator Service</a> ( <code>roles/ storage.annotationGeneratorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.objects.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code>roles/ firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudStorageOperator">Backup and DR Cloud Storage Operator</a> ( <code>roles/ backupdr.cloudStorageOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.storageaccess">Velostrata Storage Access</a> ( <code>roles/ cloudmigration.storageaccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code>roles/ config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataOwner">Dataplex Storage Data Owner</a> ( <code>roles/ dataplex.storageDataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataWriter">Dataplex Storage Data Writer</a> ( <code>roles/ dataplex.storageDataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceInput">Storage Express Mode Service Input</a> ( <code>roles/ storage.expressModeServiceInput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceOutput">Storage Express Mode Service Output</a> ( <code>roles/ storage.expressModeServiceOutput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal#aiedgeportal.serviceAgent">AI Edge Portal Service Agent</a> ( <code>roles/ aiedgeportal.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentSandboxServiceAgent">Vertex AI Agent Sandbox Service Agent</a> ( <code>roles/ aiplatform.agentSandboxServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code>roles/ aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code>roles/ aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code>roles/ automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a> ( <code>roles/ cloudasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a> ( <code>roles/ cloudoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code>roles/ contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.managedStorageServiceAgent">Data Studio Managed Storage Service Agent</a> ( <code>roles/ datastudio.managedStorageServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.serviceAgent">Device Run Service Agent</a> ( <code>roles/ devicerun.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code>roles/ documentaicore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code>roles/ firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#firestore.serviceAgent">Firestore Service Agent</a> ( <code>roles/ firestore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.serviceAgent">Live Stream Service Agent</a> ( <code>roles/ livestream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mediaasset#mediaasset.serviceAgent">Media Asset Service Agent</a> ( <code>roles/ mediaasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code>roles/ runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code>roles/ spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.serviceAgent">Transcoder Service Agent</a> ( <code>roles/ transcoder.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.objects.deleteContext</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code>roles/ storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.annotationGeneratorService">Storage Annotation Generator Service</a> ( <code>roles/ storage.annotationGeneratorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.objects.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code>roles/ firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.builder">Cloud Run Builder</a> ( <code>roles/ run.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code>roles/ storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectReader">Storage Legacy Object Reader</a> ( <code>roles/ storage.legacyObjectReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code>roles/ storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code>roles/ artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudStorageOperator">Backup and DR Cloud Storage Operator</a> ( <code>roles/ backupdr.cloudStorageOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.worker">Task Worker</a> ( <code>roles/ bigquerymigration.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.jobRunner">Cloud Deploy Runner</a> ( <code>roles/ clouddeploy.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.storageaccess">Velostrata Storage Access</a> ( <code>roles/ cloudmigration.storageaccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code>roles/ cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code>roles/ config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataOwner">Dataplex Storage Data Owner</a> ( <code>roles/ dataplex.storageDataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataReader">Dataplex Storage Data Reader</a> ( <code>roles/ dataplex.storageDataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code>roles/ dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.annotationGeneratorService">Storage Annotation Generator Service</a> ( <code>roles/ storage.annotationGeneratorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceOutput">Storage Express Mode Service Output</a> ( <code>roles/ storage.expressModeServiceOutput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal#aiedgeportal.serviceAgent">AI Edge Portal Service Agent</a> ( <code>roles/ aiedgeportal.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentSandboxServiceAgent">Vertex AI Agent Sandbox Service Agent</a> ( <code>roles/ aiplatform.agentSandboxServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code>roles/ aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionServiceAgent">Vertex AI Extension Service Agent</a> ( <code>roles/ aiplatform.extensionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code>roles/ aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code>roles/ automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a> ( <code>roles/ cloudasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a> ( <code>roles/ clouddeploy.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a> ( <code>roles/ cloudoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code>roles/ cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code>roles/ compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code>roles/ container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerregistry#containerregistry.ServiceAgent">Container Registry Service Agent</a> ( <code>roles/ containerregistry.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code>roles/ containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code>roles/ contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code>roles/ datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.discoveryServiceAgent">Dataplex Discovery Service Agent</a> ( <code>roles/ dataplex.discoveryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code>roles/ datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.managedStorageServiceAgent">Data Studio Managed Storage Service Agent</a> ( <code>roles/ datastudio.managedStorageServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.serviceAgent">Device Run Service Agent</a> ( <code>roles/ devicerun.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code>roles/ documentaicore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code>roles/ enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code>roles/ firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasetelemetry#firebasetelemetry.serviceAgent">Firebase Telemetry Service Agent</a> ( <code>roles/ firebasetelemetry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#firestore.serviceAgent">Firestore Service Agent</a> ( <code>roles/ firestore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/generativelanguage#generativelanguage.serviceAgent">Generative Language Service Agent</a> ( <code>roles/ generativelanguage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.serviceAgent">Live Stream Service Agent</a> ( <code>roles/ livestream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code>roles/ managedflink.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mediaasset#mediaasset.serviceAgent">Media Asset Service Agent</a> ( <code>roles/ mediaasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.serviceAgent">Migration Center Service Agent</a> ( <code>roles/ migrationcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.serviceAgent">Route Optimization Service Agent</a> ( <code>roles/ routeoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code>roles/ runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code>roles/ spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a> ( <code>roles/ speech.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code>roles/ stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.serviceAgent">Transcoder Service Agent</a> ( <code>roles/ transcoder.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code>roles/ vectorsearch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.objects.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code>roles/ storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerregistry#containerregistry.ServiceAgent">Container Registry Service Agent</a> ( <code>roles/ containerregistry.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code>roles/ firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.objects.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code>roles/ firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code>roles/ storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code>roles/ storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code>roles/ artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudStorageOperator">Backup and DR Cloud Storage Operator</a> ( <code>roles/ backupdr.cloudStorageOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.orchestrator">Task Orchestrator</a> ( <code>roles/ bigquerymigration.orchestrator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.worker">Task Worker</a> ( <code>roles/ bigquerymigration.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.jobRunner">Cloud Deploy Runner</a> ( <code>roles/ clouddeploy.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.storageaccess">Velostrata Storage Access</a> ( <code>roles/ cloudmigration.storageaccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code>roles/ cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code>roles/ config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataOwner">Dataplex Storage Data Owner</a> ( <code>roles/ dataplex.storageDataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataReader">Dataplex Storage Data Reader</a> ( <code>roles/ dataplex.storageDataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code>roles/ dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.annotationGeneratorService">Storage Annotation Generator Service</a> ( <code>roles/ storage.annotationGeneratorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceInput">Storage Express Mode Service Input</a> ( <code>roles/ storage.expressModeServiceInput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceOutput">Storage Express Mode Service Output</a> ( <code>roles/ storage.expressModeServiceOutput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentSandboxServiceAgent">Vertex AI Agent Sandbox Service Agent</a> ( <code>roles/ aiplatform.agentSandboxServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code>roles/ aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code>roles/ aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code>roles/ automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code>roles/ binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a> ( <code>roles/ cloudoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code>roles/ cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code>roles/ compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code>roles/ container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerregistry#containerregistry.ServiceAgent">Container Registry Service Agent</a> ( <code>roles/ containerregistry.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code>roles/ containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code>roles/ contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code>roles/ datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.discoveryServiceAgent">Dataplex Discovery Service Agent</a> ( <code>roles/ dataplex.discoveryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code>roles/ datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.managedStorageServiceAgent">Data Studio Managed Storage Service Agent</a> ( <code>roles/ datastudio.managedStorageServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code>roles/ documentaicore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code>roles/ enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code>roles/ firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#firestore.serviceAgent">Firestore Service Agent</a> ( <code>roles/ firestore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.serviceAgent">Live Stream Service Agent</a> ( <code>roles/ livestream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.serviceAgent">Route Optimization Service Agent</a> ( <code>roles/ routeoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code>roles/ runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code>roles/ spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a> ( <code>roles/ speech.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code>roles/ stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code>roles/ vectorsearch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.objects.move</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage. objects. overrideUnlockedRetention</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code>roles/ storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.objects.restore</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.objects.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code>roles/ storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.objects.setRetention</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code>roles/ storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code>roles/ storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>storage.objects.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code>roles/ firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code>roles/ storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.storageaccess">Velostrata Storage Access</a> ( <code>roles/ cloudmigration.storageaccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code>roles/ config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataOwner">Dataplex Storage Data Owner</a> ( <code>roles/ dataplex.storageDataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataWriter">Dataplex Storage Data Writer</a> ( <code>roles/ dataplex.storageDataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.annotationGeneratorService">Storage Annotation Generator Service</a> ( <code>roles/ storage.annotationGeneratorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceInput">Storage Express Mode Service Input</a> ( <code>roles/ storage.expressModeServiceInput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code>roles/ aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code>roles/ aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code>roles/ automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a> ( <code>roles/ cloudoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code>roles/ contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code>roles/ documentaicore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code>roles/ firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.serviceAgent">Live Stream Service Agent</a> ( <code>roles/ livestream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.serviceAgent">Route Optimization Service Agent</a> ( <code>roles/ routeoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a> ( <code>roles/ speech.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>storage.objects.updateContext</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code>roles/ storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code>roles/ storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.annotationGeneratorService">Storage Annotation Generator Service</a> ( <code>roles/ storage.annotationGeneratorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
