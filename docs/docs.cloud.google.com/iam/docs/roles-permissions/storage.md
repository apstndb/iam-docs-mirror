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
<td><h4 id="storage.admin" class="role-title add-link" data-text="Storage Admin" tabindex="-1">Storage Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p>Grants full control of objects and buckets.</p>
<p>When applied to an individual <strong>bucket</strong> , control applies only to the specified bucket and objects within the bucket.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudaicompanion.  instances.  completeTask</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></p>
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
<tr class="even">
<td><h4 id="storage.bucketViewer" class="role-title add-link" data-text="Storage Bucket Viewer Beta" tabindex="-1">Storage Bucket Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  storage.bucketViewer</code> )</p>
<p>Grants permission to view buckets and their metadata, excluding IAM policies.</p></td>
<td><p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="storage.editor" class="role-title add-link" data-text="Storage Editor" tabindex="-1">Storage Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p>Editor role for storage</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.delete</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  viewIntelligenceDetails</code></p>
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
<p><code dir="ltr" translate="no">storage.hmacKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.hmacKeys.create</code></li>
<li><code dir="ltr" translate="no">storage.hmacKeys.delete</code></li>
<li><code dir="ltr" translate="no">storage.hmacKeys.get</code></li>
<li><code dir="ltr" translate="no">storage.hmacKeys.list</code></li>
<li><code dir="ltr" translate="no">storage.hmacKeys.update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.  intelligenceConfigs.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="storage.folderAdmin" class="role-title add-link" data-text="Storage Folder Admin" tabindex="-1">Storage Folder Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p>Grants full control over folders and objects, including listing, creating, viewing, and deleting objects.</p></td>
<td><p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.folders.create</code></li>
<li><code dir="ltr" translate="no">storage.folders.delete</code></li>
<li><code dir="ltr" translate="no">storage.folders.get</code></li>
<li><code dir="ltr" translate="no">storage.folders.list</code></li>
<li><code dir="ltr" translate="no">storage.folders.rename</code></li>
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
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.legacyBucketOwner" class="role-title add-link" data-text="Storage Legacy Bucket Owner" tabindex="-1">Storage Legacy Bucket Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p>Grants permission to create, overwrite, and delete objects; list objects in a bucket and read object metadata, excluding allow policies, when listing; and read and edit bucket metadata, including allow policies.</p>
<p>Use of this role is also reflected in the bucket's ACLs. For more information, see <a href="https://docs.cloud.google.com/storage/docs/access-control/iam#acls">IAM relation to ACLs</a> .</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code dir="ltr" translate="no">storage.anywhereCaches.*</code></p>
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
<p><code dir="ltr" translate="no">storage.  buckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  enableObjectRetention</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIpFilter</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">storage.buckets.relocate</code></p>
<p><code dir="ltr" translate="no">storage.buckets.restore</code></p>
<p><code dir="ltr" translate="no">storage.buckets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.setIpFilter</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p>
<p><code dir="ltr" translate="no">storage.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.folders.create</code></li>
<li><code dir="ltr" translate="no">storage.folders.delete</code></li>
<li><code dir="ltr" translate="no">storage.folders.get</code></li>
<li><code dir="ltr" translate="no">storage.folders.list</code></li>
<li><code dir="ltr" translate="no">storage.folders.rename</code></li>
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
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.createContext</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.deleteContext</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.restore</code></p>
<p><code dir="ltr" translate="no">storage.objects.setRetention</code></p>
<p><code dir="ltr" translate="no">storage.objects.updateContext</code></p></td>
</tr>
<tr class="even">
<td><h4 id="storage.legacyBucketReader" class="role-title add-link" data-text="Storage Legacy Bucket Reader" tabindex="-1">Storage Legacy Bucket Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.legacyBucketReader</code> )</p>
<p>Grants permission to list a bucket's contents and read bucket metadata, excluding allow policies. Also grants permission to read object metadata, excluding allow policies, when listing objects.</p>
<p>Use of this role is also reflected in the bucket's ACLs. For more information, see <a href="https://docs.cloud.google.com/storage/docs/access-control/iam#acls">IAM relation to ACLs</a> .</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.multipartUploads.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="storage.legacyBucketWriter" class="role-title add-link" data-text="Storage Legacy Bucket Writer" tabindex="-1">Storage Legacy Bucket Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p>Grants permission to create, overwrite, and delete objects; list objects in a bucket and read object metadata, excluding allow policies, when listing; and read bucket metadata, excluding allow policies.</p>
<p>Use of this role is also reflected in the bucket's ACLs. For more information, see <a href="https://docs.cloud.google.com/storage/docs/access-control/iam#acls">IAM relation to ACLs</a> .</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code dir="ltr" translate="no">storage.buckets.get</code></p>
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
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.createContext</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.restore</code></p>
<p><code dir="ltr" translate="no">storage.objects.setRetention</code></p></td>
</tr>
<tr class="even">
<td><h4 id="storage.legacyObjectOwner" class="role-title add-link" data-text="Storage Legacy Object Owner" tabindex="-1">Storage Legacy Object Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.legacyObjectOwner</code> )</p>
<p>Grants permission to view and edit objects and their metadata, including ACLs.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code dir="ltr" translate="no">storage.objects.createContext</code></p>
<p><code dir="ltr" translate="no">storage.objects.deleteContext</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.  objects.  overrideUnlockedRetention</code></p>
<p><code dir="ltr" translate="no">storage.objects.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.objects.setRetention</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p>
<p><code dir="ltr" translate="no">storage.objects.updateContext</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="storage.legacyObjectReader" class="role-title add-link" data-text="Storage Legacy Object Reader" tabindex="-1">Storage Legacy Object Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.legacyObjectReader</code> )</p>
<p>Grants permission to view objects and their metadata, excluding ACLs.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code dir="ltr" translate="no">storage.objects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="storage.objectAdmin" class="role-title add-link" data-text="Storage Object Admin" tabindex="-1">Storage Object Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p>Grants full control of objects, including listing, creating, viewing, and deleting objects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
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
<td><h4 id="storage.objectCreator" class="role-title add-link" data-text="Storage Object Creator" tabindex="-1">Storage Object Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.objectCreator</code> )</p>
<p>Allows users to create objects. Does not give permission to view, delete, or overwrite objects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.folders.create</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.create</code></p>
<p><code dir="ltr" translate="no">storage.multipartUploads.abort</code></p>
<p><code dir="ltr" translate="no">storage.  multipartUploads.  create</code></p>
<p><code dir="ltr" translate="no">storage.  multipartUploads.  listParts</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.createContext</code></p></td>
</tr>
<tr class="even">
<td><h4 id="storage.objectUser" class="role-title add-link" data-text="Storage Object User" tabindex="-1">Storage Object User</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p>Access to create, read, update and delete objects and multipart uploads in GCS.</p></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
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
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.createContext</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.deleteContext</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.move</code></p>
<p><code dir="ltr" translate="no">storage.objects.restore</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p>
<p><code dir="ltr" translate="no">storage.objects.updateContext</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="storage.objectViewer" class="role-title add-link" data-text="Storage Object Viewer" tabindex="-1">Storage Object Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.objectViewer</code> )</p>
<p>Grants access to view objects and their metadata, excluding ACLs. Can also list the objects in a bucket.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Bucket</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.folders.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="storage.viewer" class="role-title add-link" data-text="Storage Viewer" tabindex="-1">Storage Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p>Viewer role for storage</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  viewIntelligenceDetails</code></p>
<p><code dir="ltr" translate="no">storage.featureConfigs.get</code></p>
<p><code dir="ltr" translate="no">storage.featureConfigs.list</code></p>
<p><code dir="ltr" translate="no">storage.folders.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.hmacKeys.get</code></p>
<p><code dir="ltr" translate="no">storage.hmacKeys.list</code></p>
<p><code dir="ltr" translate="no">storage.  intelligenceConfigs.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="storage.annotationGeneratorService" class="role-title add-link" data-text="Storage Annotation Generator Service Beta" tabindex="-1">Storage Annotation Generator Service <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  storage.annotationGeneratorService</code> )</p>
<p>Grants all permissions needed to generate annotations for objects in a bucket.</p></td>
<td><p><code dir="ltr" translate="no">storage.objects.createContext</code></p>
<p><code dir="ltr" translate="no">storage.objects.deleteContext</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p>
<p><code dir="ltr" translate="no">storage.objects.updateContext</code></p></td>
</tr>
<tr class="even">
<td><h4 id="storage.expressModeServiceInput" class="role-title add-link" data-text="Storage Express Mode Service Input Beta" tabindex="-1">Storage Express Mode Service Input <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  storage.expressModeServiceInput</code> )</p>
<p>Grants permission to Express Mode service accounts at a managed folder so they can create objects but not read them on input folders.</p></td>
<td><p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="storage.expressModeServiceOutput" class="role-title add-link" data-text="Storage Express Mode Service Output Beta" tabindex="-1">Storage Express Mode Service Output <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  storage.expressModeServiceOutput</code> )</p>
<p>Grants permission to Express Mode service accounts at a managed folder so they can read objects but not write them on output folders.</p></td>
<td><p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="storage.expressModeUserAccess" class="role-title add-link" data-text="Storage Express Mode User Access Beta" tabindex="-1">Storage Express Mode User Access <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p>Grants permission to Express Mode accounts at the project level so they can read, list, create and delete any object in any of their buckets in Express Mode.</p></td>
<td><p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.multipartUploads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.multipartUploads.abort</code></li>
<li><code dir="ltr" translate="no">storage.  multipartUploads.  create</code></li>
<li><code dir="ltr" translate="no">storage.multipartUploads.list</code></li>
<li><code dir="ltr" translate="no">storage.  multipartUploads.  listParts</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.restore</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="storage.hmacKeyAdmin" class="role-title add-link" data-text="Storage HMAC Key Admin" tabindex="-1">Storage HMAC Key Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.hmacKeyAdmin</code> )</p>
<p>Full control of Cloud Storage HMAC keys.</p></td>
<td><p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.hmacKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.hmacKeys.create</code></li>
<li><code dir="ltr" translate="no">storage.hmacKeys.delete</code></li>
<li><code dir="ltr" translate="no">storage.hmacKeys.get</code></li>
<li><code dir="ltr" translate="no">storage.hmacKeys.list</code></li>
<li><code dir="ltr" translate="no">storage.hmacKeys.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.insightsCollectorService" class="role-title add-link" data-text="Storage Insights Collector Service" tabindex="-1">Storage Insights Collector Service</h4>
<p>( <code dir="ltr" translate="no">roles/  storage.insightsCollectorService</code> )</p>
<p>Read-only access to Cloud Storage Inventory metadata for Storage Insights.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  getObjectInsights</code></p></td>
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
<td><h4 id="storage.anywhereCaches.create" class="permission-name add-link" data-text="storage.anywhereCaches.create" tabindex="-1"><code dir="ltr" translate="no">storage.anywhereCaches.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.anywhereCaches.disable" class="permission-name add-link" data-text="storage.anywhereCaches.disable" tabindex="-1"><code dir="ltr" translate="no">storage.anywhereCaches.disable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.anywhereCaches.get" class="permission-name add-link" data-text="storage.anywhereCaches.get" tabindex="-1"><code dir="ltr" translate="no">storage.anywhereCaches.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.anywhereCaches.list" class="permission-name add-link" data-text="storage.anywhereCaches.list" tabindex="-1"><code dir="ltr" translate="no">storage.anywhereCaches.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.anywhereCaches.pause" class="permission-name add-link" data-text="storage.anywhereCaches.pause" tabindex="-1"><code dir="ltr" translate="no">storage.anywhereCaches.pause</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.anywhereCaches.resume" class="permission-name add-link" data-text="storage.anywhereCaches.resume" tabindex="-1"><code dir="ltr" translate="no">storage.anywhereCaches.resume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.anywhereCaches.update" class="permission-name add-link" data-text="storage.anywhereCaches.update" tabindex="-1"><code dir="ltr" translate="no">storage.anywhereCaches.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.bucketOperations.cancel" class="permission-name add-link" data-text="storage.bucketOperations.cancel" tabindex="-1"><code dir="ltr" translate="no">storage.  bucketOperations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.bucketOperations.get" class="permission-name add-link" data-text="storage.bucketOperations.get" tabindex="-1"><code dir="ltr" translate="no">storage.bucketOperations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.bucketOperations.list" class="permission-name add-link" data-text="storage.bucketOperations.list" tabindex="-1"><code dir="ltr" translate="no">storage.bucketOperations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.buckets.create" class="permission-name add-link" data-text="storage.buckets.create" tabindex="-1"><code dir="ltr" translate="no">storage.buckets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudStorageOperator">Backup and DR Cloud Storage Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.cloudStorageOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal#aiedgeportal.serviceAgent">AI Edge Portal Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiedgeportal.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.buckets.createTagBinding" class="permission-name add-link" data-text="storage.buckets.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">storage.  buckets.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.buckets.delete" class="permission-name add-link" data-text="storage.buckets.delete" tabindex="-1"><code dir="ltr" translate="no">storage.buckets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.buckets.deleteTagBinding" class="permission-name add-link" data-text="storage.buckets.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">storage.  buckets.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.buckets.enableObjectRetention" class="permission-name add-link" data-text="storage.buckets.enableObjectRetention" tabindex="-1"><code dir="ltr" translate="no">storage.  buckets.  enableObjectRetention</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.buckets.get" class="permission-name add-link" data-text="storage.buckets.get" tabindex="-1"><code dir="ltr" translate="no">storage.buckets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.bucketViewer">Storage Bucket Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.bucketViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudStorageOperator">Backup and DR Cloud Storage Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.cloudStorageOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataOwner">Dataplex Storage Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.storageDataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataReader">Dataplex Storage Data Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.storageDataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.insightsCollectorService">Storage Insights Collector Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.insightsCollectorService</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal#aiedgeportal.serviceAgent">AI Edge Portal Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiedgeportal.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.discoveryServiceAgent">Dataplex Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.discoveryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentaicore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#firestore.serviceAgent">Firestore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firestore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/generativelanguage#generativelanguage.serviceAgent">Generative Language Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  generativelanguage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kuberun#kuberun.eventsControlPlaneServiceAgent">KubeRun Events Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kuberun.eventsControlPlaneServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.serviceAgent">Route Optimization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityResponseServiceAgent">Google Cloud Security Response Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityResponseServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.buckets.getIamPolicy" class="permission-name add-link" data-text="storage.buckets.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.buckets.getIpFilter" class="permission-name add-link" data-text="storage.buckets.getIpFilter" tabindex="-1"><code dir="ltr" translate="no">storage.buckets.getIpFilter</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.buckets.getObjectInsights" class="permission-name add-link" data-text="storage.buckets.getObjectInsights" tabindex="-1"><code dir="ltr" translate="no">storage.  buckets.  getObjectInsights</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.insightsCollectorService">Storage Insights Collector Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.insightsCollectorService</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.buckets.list" class="permission-name add-link" data-text="storage.buckets.list" tabindex="-1"><code dir="ltr" translate="no">storage.buckets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.bucketViewer">Storage Bucket Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.bucketViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal#aiedgeportal.serviceAgent">AI Edge Portal Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiedgeportal.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.buckets.listEffectiveTags" class="permission-name add-link" data-text="storage.buckets.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.buckets.listTagBindings" class="permission-name add-link" data-text="storage.buckets.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.buckets.relocate" class="permission-name add-link" data-text="storage.buckets.relocate" tabindex="-1"><code dir="ltr" translate="no">storage.buckets.relocate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.buckets.restore" class="permission-name add-link" data-text="storage.buckets.restore" tabindex="-1"><code dir="ltr" translate="no">storage.buckets.restore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.buckets.setIamPolicy" class="permission-name add-link" data-text="storage.buckets.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">storage.buckets.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.buckets.setIpFilter" class="permission-name add-link" data-text="storage.buckets.setIpFilter" tabindex="-1"><code dir="ltr" translate="no">storage.buckets.setIpFilter</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.buckets.update" class="permission-name add-link" data-text="storage.buckets.update" tabindex="-1"><code dir="ltr" translate="no">storage.buckets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kuberun#kuberun.eventsControlPlaneServiceAgent">KubeRun Events Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kuberun.eventsControlPlaneServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityResponseServiceAgent">Google Cloud Security Response Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityResponseServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.buckets.viewIntelligenceDetails" class="permission-name add-link" data-text="storage.buckets.viewIntelligenceDetails" tabindex="-1"><code dir="ltr" translate="no">storage.  buckets.  viewIntelligenceDetails</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.featureConfigs.create" class="permission-name add-link" data-text="storage.featureConfigs.create" tabindex="-1"><code dir="ltr" translate="no">storage.featureConfigs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.featureConfigs.delete" class="permission-name add-link" data-text="storage.featureConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">storage.featureConfigs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.featureConfigs.get" class="permission-name add-link" data-text="storage.featureConfigs.get" tabindex="-1"><code dir="ltr" translate="no">storage.featureConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.featureConfigs.list" class="permission-name add-link" data-text="storage.featureConfigs.list" tabindex="-1"><code dir="ltr" translate="no">storage.featureConfigs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.featureConfigs.update" class="permission-name add-link" data-text="storage.featureConfigs.update" tabindex="-1"><code dir="ltr" translate="no">storage.featureConfigs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.folders.create" class="permission-name add-link" data-text="storage.folders.create" tabindex="-1"><code dir="ltr" translate="no">storage.folders.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.folders.delete" class="permission-name add-link" data-text="storage.folders.delete" tabindex="-1"><code dir="ltr" translate="no">storage.folders.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.folders.get" class="permission-name add-link" data-text="storage.folders.get" tabindex="-1"><code dir="ltr" translate="no">storage.folders.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.folders.list" class="permission-name add-link" data-text="storage.folders.list" tabindex="-1"><code dir="ltr" translate="no">storage.folders.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.folders.rename" class="permission-name add-link" data-text="storage.folders.rename" tabindex="-1"><code dir="ltr" translate="no">storage.folders.rename</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.hmacKeys.create" class="permission-name add-link" data-text="storage.hmacKeys.create" tabindex="-1"><code dir="ltr" translate="no">storage.hmacKeys.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.hmacKeyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.hmacKeys.delete" class="permission-name add-link" data-text="storage.hmacKeys.delete" tabindex="-1"><code dir="ltr" translate="no">storage.hmacKeys.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.hmacKeyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storage.hmacKeys.get" class="permission-name add-link" data-text="storage.hmacKeys.get" tabindex="-1"><code dir="ltr" translate="no">storage.hmacKeys.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.hmacKeyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storage.hmacKeys.list" class="permission-name add-link" data-text="storage.hmacKeys.list" tabindex="-1"><code dir="ltr" translate="no">storage.hmacKeys.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.hmacKeyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storage.hmacKeys.update" class="permission-name add-link" data-text="storage.hmacKeys.update" tabindex="-1"><code dir="ltr" translate="no">storage.hmacKeys.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.hmacKeyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storage.intelligenceConfigs.get" class="permission-name add-link" data-text="storage.intelligenceConfigs.get" tabindex="-1"><code dir="ltr" translate="no">storage.  intelligenceConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.intelligenceConfigs.update" class="permission-name add-link" data-text="storage.intelligenceConfigs.update" tabindex="-1"><code dir="ltr" translate="no">storage.  intelligenceConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.managedFolders.create" class="permission-name add-link" data-text="storage.managedFolders.create" tabindex="-1"><code dir="ltr" translate="no">storage.managedFolders.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.managedFolders.delete" class="permission-name add-link" data-text="storage.managedFolders.delete" tabindex="-1"><code dir="ltr" translate="no">storage.managedFolders.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.managedFolders.get" class="permission-name add-link" data-text="storage.managedFolders.get" tabindex="-1"><code dir="ltr" translate="no">storage.managedFolders.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.managedFolders.getIamPolicy" class="permission-name add-link" data-text="storage.managedFolders.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">storage.  managedFolders.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.managedFolders.list" class="permission-name add-link" data-text="storage.managedFolders.list" tabindex="-1"><code dir="ltr" translate="no">storage.managedFolders.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.managedFolders.setIamPolicy" class="permission-name add-link" data-text="storage.managedFolders.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">storage.  managedFolders.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.multipartUploads.abort" class="permission-name add-link" data-text="storage.multipartUploads.abort" tabindex="-1"><code dir="ltr" translate="no">storage.multipartUploads.abort</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.multipartUploads.create" class="permission-name add-link" data-text="storage.multipartUploads.create" tabindex="-1"><code dir="ltr" translate="no">storage.  multipartUploads.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.multipartUploads.list" class="permission-name add-link" data-text="storage.multipartUploads.list" tabindex="-1"><code dir="ltr" translate="no">storage.multipartUploads.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.multipartUploads.listParts" class="permission-name add-link" data-text="storage.multipartUploads.listParts" tabindex="-1"><code dir="ltr" translate="no">storage.  multipartUploads.  listParts</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.objects.create" class="permission-name add-link" data-text="storage.objects.create" tabindex="-1"><code dir="ltr" translate="no">storage.objects.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudStorageOperator">Backup and DR Cloud Storage Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.cloudStorageOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.worker">Task Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.jobRunner">Cloud Deploy Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.storageaccess">Velostrata Storage Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.storageaccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataOwner">Dataplex Storage Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.storageDataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataWriter">Dataplex Storage Data Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.storageDataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceInput">Storage Express Mode Service Input</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeServiceInput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal#aiedgeportal.serviceAgent">AI Edge Portal Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiedgeportal.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentSandboxServiceAgent">Vertex AI Agent Sandbox Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.agentSandboxServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentaicore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#firestore.serviceAgent">Firestore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firestore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.serviceAgent">Live Stream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mediaasset#mediaasset.serviceAgent">Media Asset Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mediaasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.serviceAgent">Route Optimization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.serviceAgent">Transcoder Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.objects.createContext" class="permission-name add-link" data-text="storage.objects.createContext" tabindex="-1"><code dir="ltr" translate="no">storage.objects.createContext</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.annotationGeneratorService">Storage Annotation Generator Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.annotationGeneratorService</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.objects.delete" class="permission-name add-link" data-text="storage.objects.delete" tabindex="-1"><code dir="ltr" translate="no">storage.objects.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudStorageOperator">Backup and DR Cloud Storage Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.cloudStorageOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.storageaccess">Velostrata Storage Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.storageaccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataOwner">Dataplex Storage Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.storageDataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataWriter">Dataplex Storage Data Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.storageDataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceInput">Storage Express Mode Service Input</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeServiceInput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceOutput">Storage Express Mode Service Output</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeServiceOutput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal#aiedgeportal.serviceAgent">AI Edge Portal Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiedgeportal.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentSandboxServiceAgent">Vertex AI Agent Sandbox Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.agentSandboxServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentaicore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#firestore.serviceAgent">Firestore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firestore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.serviceAgent">Live Stream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mediaasset#mediaasset.serviceAgent">Media Asset Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mediaasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.serviceAgent">Transcoder Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.objects.deleteContext" class="permission-name add-link" data-text="storage.objects.deleteContext" tabindex="-1"><code dir="ltr" translate="no">storage.objects.deleteContext</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.annotationGeneratorService">Storage Annotation Generator Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.annotationGeneratorService</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.objects.get" class="permission-name add-link" data-text="storage.objects.get" tabindex="-1"><code dir="ltr" translate="no">storage.objects.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.builder">Cloud Run Builder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectReader">Storage Legacy Object Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyObjectReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudStorageOperator">Backup and DR Cloud Storage Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.cloudStorageOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.worker">Task Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.jobRunner">Cloud Deploy Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.storageaccess">Velostrata Storage Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.storageaccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataOwner">Dataplex Storage Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.storageDataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataReader">Dataplex Storage Data Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.storageDataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.annotationGeneratorService">Storage Annotation Generator Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.annotationGeneratorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceOutput">Storage Express Mode Service Output</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeServiceOutput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal#aiedgeportal.serviceAgent">AI Edge Portal Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiedgeportal.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentSandboxServiceAgent">Vertex AI Agent Sandbox Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.agentSandboxServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionServiceAgent">Vertex AI Extension Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerregistry#containerregistry.ServiceAgent">Container Registry Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerregistry.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.discoveryServiceAgent">Dataplex Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.discoveryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentaicore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#firestore.serviceAgent">Firestore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firestore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/generativelanguage#generativelanguage.serviceAgent">Generative Language Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  generativelanguage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.serviceAgent">Live Stream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mediaasset#mediaasset.serviceAgent">Media Asset Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mediaasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.serviceAgent">Migration Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.serviceAgent">Route Optimization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.serviceAgent">Transcoder Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.objects.getIamPolicy" class="permission-name add-link" data-text="storage.objects.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerregistry#containerregistry.ServiceAgent">Container Registry Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerregistry.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.objects.list" class="permission-name add-link" data-text="storage.objects.list" tabindex="-1"><code dir="ltr" translate="no">storage.objects.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketReader">Storage Legacy Bucket Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudStorageOperator">Backup and DR Cloud Storage Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.cloudStorageOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.orchestrator">Task Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.orchestrator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.worker">Task Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.jobRunner">Cloud Deploy Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.storageaccess">Velostrata Storage Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.storageaccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataOwner">Dataplex Storage Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.storageDataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataReader">Dataplex Storage Data Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.storageDataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.annotationGeneratorService">Storage Annotation Generator Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.annotationGeneratorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceInput">Storage Express Mode Service Input</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeServiceInput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceOutput">Storage Express Mode Service Output</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeServiceOutput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentSandboxServiceAgent">Vertex AI Agent Sandbox Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.agentSandboxServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerregistry#containerregistry.ServiceAgent">Container Registry Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerregistry.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.discoveryServiceAgent">Dataplex Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.discoveryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentaicore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#firestore.serviceAgent">Firestore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firestore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.serviceAgent">Live Stream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.serviceAgent">Route Optimization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.objects.move" class="permission-name add-link" data-text="storage.objects.move" tabindex="-1"><code dir="ltr" translate="no">storage.objects.move</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.objects.overrideUnlockedRetention" class="permission-name add-link" data-text="storage.objects.overrideUnlockedRetention" tabindex="-1"><code dir="ltr" translate="no">storage.  objects.  overrideUnlockedRetention</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.objects.restore" class="permission-name add-link" data-text="storage.objects.restore" tabindex="-1"><code dir="ltr" translate="no">storage.objects.restore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.objects.setIamPolicy" class="permission-name add-link" data-text="storage.objects.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">storage.objects.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.objects.setRetention" class="permission-name add-link" data-text="storage.objects.setRetention" tabindex="-1"><code dir="ltr" translate="no">storage.objects.setRetention</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketWriter">Storage Legacy Bucket Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storage.objects.update" class="permission-name add-link" data-text="storage.objects.update" tabindex="-1"><code dir="ltr" translate="no">storage.objects.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.storageaccess">Velostrata Storage Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.storageaccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataOwner">Dataplex Storage Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.storageDataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.storageDataWriter">Dataplex Storage Data Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.storageDataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.annotationGeneratorService">Storage Annotation Generator Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.annotationGeneratorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeServiceInput">Storage Express Mode Service Input</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeServiceInput</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.expressModeUserAccess</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.batchPredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentaicore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.serviceAgent">Live Stream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.serviceAgent">Route Optimization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storage.objects.updateContext" class="permission-name add-link" data-text="storage.objects.updateContext" tabindex="-1"><code dir="ltr" translate="no">storage.objects.updateContext</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyBucketOwner">Storage Legacy Bucket Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyBucketOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.legacyObjectOwner">Storage Legacy Object Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.legacyObjectOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.annotationGeneratorService">Storage Annotation Generator Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.annotationGeneratorService</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
