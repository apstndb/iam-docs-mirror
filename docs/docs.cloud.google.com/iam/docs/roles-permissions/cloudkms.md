---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudkms
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms
title: Cloud Key Management Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Key Management Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Key Management Service roles

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
<td><h4 id="cloudkms.admin" class="role-title add-link" data-text="Cloud KMS Admin" tabindex="-1">Cloud KMS Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p>Provides access to Cloud KMS resources, except for access to restricted resource types and cryptographic operations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.autokeyConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.autokeyConfigs.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.autokeyConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  create</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  delete</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  destroy</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeyVersions.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  restore</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  update</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecryptViaDelegation</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToEncryptViaDelegation</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.cryptoKeys.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.cryptoKeys.delete</code></li>
<li><code dir="ltr" translate="no">cloudkms.cryptoKeys.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.  cryptoKeys.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudkms.cryptoKeys.list</code></li>
<li><code dir="ltr" translate="no">cloudkms.  cryptoKeys.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudkms.cryptoKeys.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.ekmConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.ekmConfigs.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.  ekmConfigs.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudkms.  ekmConfigs.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudkms.ekmConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.ekmConnections.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.ekmConnections.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.ekmConnections.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.  ekmConnections.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudkms.ekmConnections.list</code></li>
<li><code dir="ltr" translate="no">cloudkms.  ekmConnections.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudkms.ekmConnections.update</code></li>
<li><code dir="ltr" translate="no">cloudkms.ekmConnections.use</code></li>
<li><code dir="ltr" translate="no">cloudkms.  ekmConnections.  verifyConnectivity</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.importJobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.importJobs.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.importJobs.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.  importJobs.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudkms.importJobs.list</code></li>
<li><code dir="ltr" translate="no">cloudkms.  importJobs.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudkms.  importJobs.  useToImport</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.kajPolicyConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.kajPolicyConfigs.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.  kajPolicyConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.keyRings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyRings.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.  keyRings.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">cloudkms.  keyRings.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyRings.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyRings.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyRings.list</code></li>
<li><code dir="ltr" translate="no">cloudkms.  keyRings.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">cloudkms.  keyRings.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyRings.setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  locations.  optOutKeyDeletionMsa</code></p>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.projects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></li>
<li><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveKajEnrollmentConfig</code></li>
<li><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveKajPolicyConfig</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.retiredResources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.retiredResources.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.retiredResources.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  delete</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  create</code></li>
<li><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  get</code></li>
<li><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  list</code></li>
<li><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyEncrypterDecrypter" class="role-title add-link" data-text="Cloud KMS CryptoKey Encrypter/Decrypter" tabindex="-1">Cloud KMS CryptoKey Encrypter/Decrypter</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypter</code> )</p>
<p>Provides ability to use Cloud KMS resources for encrypt and decrypt operations only.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecrypt</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToEncrypt</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.viewer" class="role-title add-link" data-text="Cloud KMS Viewer" tabindex="-1">Cloud KMS Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p>Enables Get and List operations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.autokeyConfigs.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeyVersions.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeys.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeys.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.ekmConfigs.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.ekmConnections.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.ekmConnections.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.importJobs.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.importJobs.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.kajPolicyConfigs.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  protectableResources.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.retiredResources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.retiredResources.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.retiredResources.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.autokeyAdmin" class="role-title add-link" data-text="Cloud KMS Autokey Admin" tabindex="-1">Cloud KMS Autokey Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.autokeyAdmin</code> )</p>
<p>Enables management of AutokeyConfig.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.autokeyConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.autokeyConfigs.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.autokeyConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.autokeyUser" class="role-title add-link" data-text="Cloud KMS Autokey User" tabindex="-1">Cloud KMS Autokey User</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.autokeyUser</code> )</p>
<p>Grants ability to use KeyHandle resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyDecrypter" class="role-title add-link" data-text="Cloud KMS CryptoKey Decrypter" tabindex="-1">Cloud KMS CryptoKey Decrypter</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.cryptoKeyDecrypter</code> )</p>
<p>Provides ability to use Cloud KMS resources for decrypt operations only.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecrypt</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeyDecrypterViaDelegation" class="role-title add-link" data-text="Cloud KMS CryptoKey Decrypter Via Delegation" tabindex="-1">Cloud KMS CryptoKey Decrypter Via Delegation</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.cryptoKeyDecrypterViaDelegation</code> )</p>
<p>Enables Decrypt operations via other Google Cloud services</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecryptViaDelegation</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyEncrypter" class="role-title add-link" data-text="Cloud KMS CryptoKey Encrypter" tabindex="-1">Cloud KMS CryptoKey Encrypter</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypter</code> )</p>
<p>Provides ability to use Cloud KMS resources for encrypt operations only.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToEncrypt</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeyEncrypterDecrypterViaDelegation" class="role-title add-link" data-text="Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation" tabindex="-1">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p>
<p>Enables Encrypt and Decrypt operations via other Google Cloud services</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecryptViaDelegation</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToEncryptViaDelegation</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyEncrypterViaDelegation" class="role-title add-link" data-text="Cloud KMS CryptoKey Encrypter Via Delegation" tabindex="-1">Cloud KMS CryptoKey Encrypter Via Delegation</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterViaDelegation</code> )</p>
<p>Enables Encrypt operations via other Google Cloud services</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToEncryptViaDelegation</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoOperator" class="role-title add-link" data-text="Cloud KMS Crypto Operator" tabindex="-1">Cloud KMS Crypto Operator</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.cryptoOperator</code> )</p>
<p>Enables all Crypto Operations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecapsulate</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecrypt</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToEncrypt</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToSign</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToVerify</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  viewPublicKey</code></p>
<p><code dir="ltr" translate="no">cloudkms.  locations.  generateRandomBytes</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.decapsulator" class="role-title add-link" data-text="Cloud KMS CryptoKey Decapsulator Beta" tabindex="-1">Cloud KMS CryptoKey Decapsulator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.decapsulator</code> )</p>
<p>Enables Decapsulate and GetPublicKey operations</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecapsulate</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  viewPublicKey</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.ekmConnectionsAdmin" class="role-title add-link" data-text="Cloud KMS EkmConnections Admin" tabindex="-1">Cloud KMS EkmConnections Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.ekmConnectionsAdmin</code> )</p>
<p>Enables management of EkmConnections.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.ekmConfigs.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.ekmConfigs.update</code></p>
<p><code dir="ltr" translate="no">cloudkms.ekmConnections.create</code></p>
<p><code dir="ltr" translate="no">cloudkms.ekmConnections.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.ekmConnections.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.ekmConnections.update</code></p>
<p><code dir="ltr" translate="no">cloudkms.  ekmConnections.  verifyConnectivity</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.encryptionDashboardViewer" class="role-title add-link" data-text="Cloud KMS Encryption Dashboard Viewer" tabindex="-1">Cloud KMS Encryption Dashboard Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.encryptionDashboardViewer</code> )</p>
<p>Enables viewing KMS encryption dashboard.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.cryptoKeys.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  protectableResources.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.expertPqcSigner" class="role-title add-link" data-text="Cloud KMS Expert PQ Asymmetric Signing Key Manager" tabindex="-1">Cloud KMS Expert PQ Asymmetric Signing Key Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.expertPqcSigner</code> )</p>
<p>Enables PQ asymmetric signing key management.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  managePqcSign</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.expertRawAesCbc" class="role-title add-link" data-text="Cloud KMS Expert Raw AES-CBC Key Manager" tabindex="-1">Cloud KMS Expert Raw AES-CBC Key Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.expertRawAesCbc</code> )</p>
<p>Enables raw AES-CBC keys management.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  manageRawAesCbcKeys</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.expertRawAesCtr" class="role-title add-link" data-text="Cloud KMS Expert Raw AES-CTR Key Manager" tabindex="-1">Cloud KMS Expert Raw AES-CTR Key Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.expertRawAesCtr</code> )</p>
<p>Enables raw AES-CTR keys management.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  manageRawAesCtrKeys</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.expertRawPKCS1" class="role-title add-link" data-text="Cloud KMS Expert Raw PKCS#1 Key Manager" tabindex="-1">Cloud KMS Expert Raw PKCS#1 Key Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.expertRawPKCS1</code> )</p>
<p>Enables raw PKCS#1 keys management.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  manageRawPKCS1Keys</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.hsmSingleTenantExecutor" class="role-title add-link" data-text="Cloud KMS single-tenant HSM Executor" tabindex="-1">Cloud KMS single-tenant HSM Executor</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantExecutor</code> )</p>
<p>Grants ability to execute SingleTenantHsmInstanceProposal resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  execute</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.hsmSingleTenantKeyCreator" class="role-title add-link" data-text="Cloud KMS single-tenant HSM Key Creator" tabindex="-1">Cloud KMS single-tenant HSM Key Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantKeyCreator</code> )</p>
<p>Grants ability to use single-tenant HSM instances to create keys. This role must be combined with another role that grants the ability to create cryptoKeys.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  use</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.hsmSingleTenantProposer" class="role-title add-link" data-text="Cloud KMS single-tenant HSM Proposer" tabindex="-1">Cloud KMS single-tenant HSM Proposer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantProposer</code> )</p>
<p>Grants ability to create SingleTenantHsmInstances and SingleTenantHsmInstanceProposals.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  create</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  delete</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  create</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.hsmSingleTenantQuorumMember" class="role-title add-link" data-text="Cloud KMS single-tenant HSM Quorum Member" tabindex="-1">Cloud KMS single-tenant HSM Quorum Member</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p>Grants ability to approve SingleTenantHsmInstanceProposal resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  approve</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.importer" class="role-title add-link" data-text="Cloud KMS Importer" tabindex="-1">Cloud KMS Importer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.importer</code> )</p>
<p>Enables ImportCryptoKeyVersion, CreateImportJob, ListImportJobs, and GetImportJob operations</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.importJobs.create</code></p>
<p><code dir="ltr" translate="no">cloudkms.importJobs.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.importJobs.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  importJobs.  useToImport</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.keyAccessJustificationsEnrollmentConfigViewer" class="role-title add-link" data-text="Key Access Justifications Enrollment Viewer" tabindex="-1">Key Access Justifications Enrollment Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.keyAccessJustificationsEnrollmentConfigViewer</code> )</p>
<p>Grant ability to view Key Access Justification enrollment configs of a project.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveKajEnrollmentConfig</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.keyAccessJustificationsPolicyConfigAdmin" class="role-title add-link" data-text="Key Access Justifications Policy Config Admin" tabindex="-1">Key Access Justifications Policy Config Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.keyAccessJustificationsPolicyConfigAdmin</code> )</p>
<p>Grant ability to manage Key Access Justifications Policy at parent resource level.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.kajPolicyConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.kajPolicyConfigs.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.  kajPolicyConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveKajPolicyConfig</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.protectedResourcesViewer" class="role-title add-link" data-text="Cloud KMS Protected Resources Viewer" tabindex="-1">Cloud KMS Protected Resources Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.protectedResourcesViewer</code> )</p>
<p>Enables viewing protected resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.  protectedResources.  search</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.publicKeyViewer" class="role-title add-link" data-text="Cloud KMS CryptoKey Public Key Viewer" tabindex="-1">Cloud KMS CryptoKey Public Key Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.publicKeyViewer</code> )</p>
<p>Enables GetPublicKey operations</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  viewPublicKey</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.signer" class="role-title add-link" data-text="Cloud KMS CryptoKey Signer" tabindex="-1">Cloud KMS CryptoKey Signer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.signer</code> )</p>
<p>Enables Sign operations</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToSign</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.signerVerifier" class="role-title add-link" data-text="Cloud KMS CryptoKey Signer/Verifier" tabindex="-1">Cloud KMS CryptoKey Signer/Verifier</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.signerVerifier</code> )</p>
<p>Enables Sign, Verify, and GetPublicKey operations</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToSign</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToVerify</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  viewPublicKey</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.verifier" class="role-title add-link" data-text="Cloud KMS CryptoKey Verifier" tabindex="-1">Cloud KMS CryptoKey Verifier</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.verifier</code> )</p>
<p>Enables Verify and GetPublicKey operations</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToVerify</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  viewPublicKey</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
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
<td><h4 id="cloudkms.orgServiceAgent" class="role-title add-link" data-text="Cloud KMS Organization Service Agent" tabindex="-1">Cloud KMS Organization Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.orgServiceAgent</code> )</p>
<p>Gives Cloud KMS organization-level service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudasset.assets.listResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllIamPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.serviceAgent" class="role-title add-link" data-text="Cloud KMS Service Agent" tabindex="-1">Cloud KMS Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkms.serviceAgent</code> )</p>
<p>Gives Cloud KMS service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudkmsCryptoKeys</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.listResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllIamPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeys.create</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeys.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.create</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkmskacls.serviceAgent" class="role-title add-link" data-text="Cloud KMS KACLS Service Agent" tabindex="-1">Cloud KMS KACLS Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudkmskacls.serviceAgent</code> )</p>
<p>Grants Cloud KMS KACLS Service Agent access to KMS resource permissions to perform DEK encryption/decryption.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecrypt</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToEncrypt</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeys.get</code></p></td>
</tr>
</tbody>
</table>

## Cloud Key Management Service permissions

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
<td><h4 id="cloudkms.autokeyConfigs.get" class="permission-name add-link" data-text="cloudkms.autokeyConfigs.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.autokeyConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyAdmin">Cloud KMS Autokey Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.autokeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.autokeyConfigs.update" class="permission-name add-link" data-text="cloudkms.autokeyConfigs.update" tabindex="-1"><code dir="ltr" translate="no">cloudkms.autokeyConfigs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyAdmin">Cloud KMS Autokey Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.autokeyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeyVersions.create" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.create" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyVersions.delete" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.delete" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeyVersions.destroy" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.destroy" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  destroy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyVersions.get" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.cryptoKeyVersions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.cloudKmsKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeyVersions.list" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.list" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyVersions.managePqcSign" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.managePqcSign" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  managePqcSign</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertPqcSigner">Cloud KMS Expert PQ Asymmetric Signing Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertPqcSigner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeyVersions.manageRawAesCbcKeys" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.manageRawAesCbcKeys" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  manageRawAesCbcKeys</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCbc">Cloud KMS Expert Raw AES-CBC Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawAesCbc</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyVersions.manageRawAesCtrKeys" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.manageRawAesCtrKeys" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  manageRawAesCtrKeys</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCtr">Cloud KMS Expert Raw AES-CTR Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawAesCtr</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeyVersions.manageRawPKCS1Keys" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.manageRawPKCS1Keys" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  manageRawPKCS1Keys</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawPKCS1">Cloud KMS Expert Raw PKCS#1 Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawPKCS1</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyVersions.restore" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.restore" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  restore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeyVersions.update" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.update" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyVersions.useToDecapsulate" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.useToDecapsulate" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecapsulate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.decapsulator">Cloud KMS CryptoKey Decapsulator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.decapsulator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeyVersions.useToDecrypt" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.useToDecrypt" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecrypt</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypter">Cloud KMS CryptoKey Encrypter/Decrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypter">Cloud KMS CryptoKey Decrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkmskacls.serviceAgent">Cloud KMS KACLS Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkmskacls.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyVersions.useToDecryptViaDelegation" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.useToDecryptViaDelegation" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecryptViaDelegation</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypterViaDelegation">Cloud KMS CryptoKey Decrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypterViaDelegation">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeyVersions.useToEncrypt" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.useToEncrypt" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToEncrypt</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypter">Cloud KMS CryptoKey Encrypter/Decrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypter">Cloud KMS CryptoKey Encrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkmskacls.serviceAgent">Cloud KMS KACLS Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkmskacls.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyVersions.useToEncryptViaDelegation" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.useToEncryptViaDelegation" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToEncryptViaDelegation</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypterViaDelegation">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterViaDelegation">Cloud KMS CryptoKey Encrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterViaDelegation</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeyVersions.useToSign" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.useToSign" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToSign</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signer">Cloud KMS CryptoKey Signer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.signer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signerVerifier">Cloud KMS CryptoKey Signer/Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.signerVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.cloudKmsKeyUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeyVersions.useToVerify" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.useToVerify" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToVerify</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signerVerifier">Cloud KMS CryptoKey Signer/Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.signerVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.verifier">Cloud KMS CryptoKey Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.cloudKmsKeyUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeyVersions.viewPublicKey" class="permission-name add-link" data-text="cloudkms.cryptoKeyVersions.viewPublicKey" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  viewPublicKey</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.decapsulator">Cloud KMS CryptoKey Decapsulator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.decapsulator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.publicKeyViewer">Cloud KMS CryptoKey Public Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.publicKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signerVerifier">Cloud KMS CryptoKey Signer/Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.signerVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.verifier">Cloud KMS CryptoKey Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.cloudKmsKeyUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeys.create" class="permission-name add-link" data-text="cloudkms.cryptoKeys.create" tabindex="-1"><code dir="ltr" translate="no">cloudkms.cryptoKeys.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.serviceAgent">Cloud KMS Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeys.delete" class="permission-name add-link" data-text="cloudkms.cryptoKeys.delete" tabindex="-1"><code dir="ltr" translate="no">cloudkms.cryptoKeys.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeys.get" class="permission-name add-link" data-text="cloudkms.cryptoKeys.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.cryptoKeys.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.cloudKmsKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkmskacls.serviceAgent">Cloud KMS KACLS Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkmskacls.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeys.getIamPolicy" class="permission-name add-link" data-text="cloudkms.cryptoKeys.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeys.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.serviceAgent">Cloud KMS Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeys.list" class="permission-name add-link" data-text="cloudkms.cryptoKeys.list" tabindex="-1"><code dir="ltr" translate="no">cloudkms.cryptoKeys.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.encryptionDashboardViewer">Cloud KMS Encryption Dashboard Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.encryptionDashboardViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.cryptoKeys.setIamPolicy" class="permission-name add-link" data-text="cloudkms.cryptoKeys.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  cryptoKeys.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.serviceAgent">Cloud KMS Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.cryptoKeys.update" class="permission-name add-link" data-text="cloudkms.cryptoKeys.update" tabindex="-1"><code dir="ltr" translate="no">cloudkms.cryptoKeys.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.ekmConfigs.get" class="permission-name add-link" data-text="cloudkms.ekmConfigs.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.ekmConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.ekmConnectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.ekmConfigs.getIamPolicy" class="permission-name add-link" data-text="cloudkms.ekmConfigs.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  ekmConfigs.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.ekmConfigs.setIamPolicy" class="permission-name add-link" data-text="cloudkms.ekmConfigs.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  ekmConfigs.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.ekmConfigs.update" class="permission-name add-link" data-text="cloudkms.ekmConfigs.update" tabindex="-1"><code dir="ltr" translate="no">cloudkms.ekmConfigs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.ekmConnectionsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.ekmConnections.create" class="permission-name add-link" data-text="cloudkms.ekmConnections.create" tabindex="-1"><code dir="ltr" translate="no">cloudkms.ekmConnections.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.ekmConnectionsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.ekmConnections.get" class="permission-name add-link" data-text="cloudkms.ekmConnections.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.ekmConnections.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.ekmConnectionsAdmin</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.ekmServiceAgent">Cloud Controls Partner EKM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.ekmServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.ekmConnections.getIamPolicy" class="permission-name add-link" data-text="cloudkms.ekmConnections.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  ekmConnections.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.ekmServiceAgent">Cloud Controls Partner EKM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.ekmServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.ekmConnections.list" class="permission-name add-link" data-text="cloudkms.ekmConnections.list" tabindex="-1"><code dir="ltr" translate="no">cloudkms.ekmConnections.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.ekmConnectionsAdmin</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.ekmServiceAgent">Cloud Controls Partner EKM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.ekmServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.ekmConnections.setIamPolicy" class="permission-name add-link" data-text="cloudkms.ekmConnections.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  ekmConnections.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.ekmConnections.update" class="permission-name add-link" data-text="cloudkms.ekmConnections.update" tabindex="-1"><code dir="ltr" translate="no">cloudkms.ekmConnections.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.ekmConnectionsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.ekmConnections.use" class="permission-name add-link" data-text="cloudkms.ekmConnections.use" tabindex="-1"><code dir="ltr" translate="no">cloudkms.ekmConnections.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.ekmConnections.verifyConnectivity" class="permission-name add-link" data-text="cloudkms.ekmConnections.verifyConnectivity" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  ekmConnections.  verifyConnectivity</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.ekmConnectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.ekmServiceAgent">Cloud Controls Partner EKM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.ekmServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.importJobs.create" class="permission-name add-link" data-text="cloudkms.importJobs.create" tabindex="-1"><code dir="ltr" translate="no">cloudkms.importJobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.importer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.importJobs.get" class="permission-name add-link" data-text="cloudkms.importJobs.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.importJobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.importJobs.getIamPolicy" class="permission-name add-link" data-text="cloudkms.importJobs.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  importJobs.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.importJobs.list" class="permission-name add-link" data-text="cloudkms.importJobs.list" tabindex="-1"><code dir="ltr" translate="no">cloudkms.importJobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.importJobs.setIamPolicy" class="permission-name add-link" data-text="cloudkms.importJobs.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  importJobs.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.importJobs.useToImport" class="permission-name add-link" data-text="cloudkms.importJobs.useToImport" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  importJobs.  useToImport</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.importer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.kajPolicyConfigs.get" class="permission-name add-link" data-text="cloudkms.kajPolicyConfigs.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.kajPolicyConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.keyAccessJustificationsPolicyConfigAdmin">Key Access Justifications Policy Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.keyAccessJustificationsPolicyConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.kajPolicyConfigs.update" class="permission-name add-link" data-text="cloudkms.kajPolicyConfigs.update" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  kajPolicyConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.keyAccessJustificationsPolicyConfigAdmin">Key Access Justifications Policy Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.keyAccessJustificationsPolicyConfigAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.keyHandles.create" class="permission-name add-link" data-text="cloudkms.keyHandles.create" tabindex="-1"><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyUser">Cloud KMS Autokey User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.autokeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.keyHandles.get" class="permission-name add-link" data-text="cloudkms.keyHandles.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyUser">Cloud KMS Autokey User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.autokeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.keyHandles.list" class="permission-name add-link" data-text="cloudkms.keyHandles.list" tabindex="-1"><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyUser">Cloud KMS Autokey User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.autokeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.keyRings.create" class="permission-name add-link" data-text="cloudkms.keyRings.create" tabindex="-1"><code dir="ltr" translate="no">cloudkms.keyRings.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.serviceAgent">Cloud KMS Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.keyRings.createTagBinding" class="permission-name add-link" data-text="cloudkms.keyRings.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  keyRings.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.keyRings.deleteTagBinding" class="permission-name add-link" data-text="cloudkms.keyRings.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  keyRings.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.keyRings.get" class="permission-name add-link" data-text="cloudkms.keyRings.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.keyRings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.serviceAgent">Cloud KMS Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.keyRings.getIamPolicy" class="permission-name add-link" data-text="cloudkms.keyRings.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudkms.keyRings.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.keyRings.list" class="permission-name add-link" data-text="cloudkms.keyRings.list" tabindex="-1"><code dir="ltr" translate="no">cloudkms.keyRings.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.keyRings.listEffectiveTags" class="permission-name add-link" data-text="cloudkms.keyRings.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  keyRings.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.keyRings.listTagBindings" class="permission-name add-link" data-text="cloudkms.keyRings.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  keyRings.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.keyRings.setIamPolicy" class="permission-name add-link" data-text="cloudkms.keyRings.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudkms.keyRings.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.locations.generateRandomBytes" class="permission-name add-link" data-text="cloudkms.locations.generateRandomBytes" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  locations.  generateRandomBytes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.locations.get" class="permission-name add-link" data-text="cloudkms.locations.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypter">Cloud KMS CryptoKey Encrypter/Decrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypter">Cloud KMS CryptoKey Decrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypterViaDelegation">Cloud KMS CryptoKey Decrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypter">Cloud KMS CryptoKey Encrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypterViaDelegation">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterViaDelegation">Cloud KMS CryptoKey Encrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.decapsulator">Cloud KMS CryptoKey Decapsulator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.decapsulator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertPqcSigner">Cloud KMS Expert PQ Asymmetric Signing Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertPqcSigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCbc">Cloud KMS Expert Raw AES-CBC Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawAesCbc</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCtr">Cloud KMS Expert Raw AES-CTR Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawAesCtr</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawPKCS1">Cloud KMS Expert Raw PKCS#1 Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawPKCS1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.publicKeyViewer">Cloud KMS CryptoKey Public Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.publicKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signer">Cloud KMS CryptoKey Signer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.signer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signerVerifier">Cloud KMS CryptoKey Signer/Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.signerVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.verifier">Cloud KMS CryptoKey Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.cloudKmsKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudkms.locations.list" class="permission-name add-link" data-text="cloudkms.locations.list" tabindex="-1"><code dir="ltr" translate="no">cloudkms.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypter">Cloud KMS CryptoKey Encrypter/Decrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypter">Cloud KMS CryptoKey Decrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypterViaDelegation">Cloud KMS CryptoKey Decrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypter">Cloud KMS CryptoKey Encrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypterViaDelegation">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterViaDelegation">Cloud KMS CryptoKey Encrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.decapsulator">Cloud KMS CryptoKey Decapsulator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.decapsulator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertPqcSigner">Cloud KMS Expert PQ Asymmetric Signing Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertPqcSigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCbc">Cloud KMS Expert Raw AES-CBC Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawAesCbc</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCtr">Cloud KMS Expert Raw AES-CTR Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawAesCtr</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawPKCS1">Cloud KMS Expert Raw PKCS#1 Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawPKCS1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.publicKeyViewer">Cloud KMS CryptoKey Public Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.publicKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signer">Cloud KMS CryptoKey Signer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.signer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signerVerifier">Cloud KMS CryptoKey Signer/Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.signerVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.verifier">Cloud KMS CryptoKey Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.cloudKmsKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudkms.locations.optOutKeyDeletionMsa" class="permission-name add-link" data-text="cloudkms.locations.optOutKeyDeletionMsa" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  locations.  optOutKeyDeletionMsa</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.operations.get" class="permission-name add-link" data-text="cloudkms.operations.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyUser">Cloud KMS Autokey User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.autokeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantExecutor">Cloud KMS single-tenant HSM Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantQuorumMember">Cloud KMS single-tenant HSM Quorum Member</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.projects.showEffectiveAutokeyConfig" class="permission-name add-link" data-text="cloudkms.projects.showEffectiveAutokeyConfig" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyAdmin">Cloud KMS Autokey Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.autokeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyUser">Cloud KMS Autokey User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.autokeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.projects.showEffectiveKajEnrollmentConfig" class="permission-name add-link" data-text="cloudkms.projects.showEffectiveKajEnrollmentConfig" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveKajEnrollmentConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.keyAccessJustificationsEnrollmentConfigViewer">Key Access Justifications Enrollment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.keyAccessJustificationsEnrollmentConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.projects.showEffectiveKajPolicyConfig" class="permission-name add-link" data-text="cloudkms.projects.showEffectiveKajPolicyConfig" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveKajPolicyConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.keyAccessJustificationsPolicyConfigAdmin">Key Access Justifications Policy Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.keyAccessJustificationsPolicyConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.protectableResources.list" class="permission-name add-link" data-text="cloudkms.protectableResources.list" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  protectableResources.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.encryptionDashboardViewer">Cloud KMS Encryption Dashboard Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.encryptionDashboardViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.protectedResources.search" class="permission-name add-link" data-text="cloudkms.protectedResources.search" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  protectedResources.  search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.protectedResourcesViewer">Cloud KMS Protected Resources Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.protectedResourcesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.retiredResources.get" class="permission-name add-link" data-text="cloudkms.retiredResources.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.retiredResources.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.retiredResources.list" class="permission-name add-link" data-text="cloudkms.retiredResources.list" tabindex="-1"><code dir="ltr" translate="no">cloudkms.retiredResources.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.singleTenantHsmInstanceProposals.approve" class="permission-name add-link" data-text="cloudkms.singleTenantHsmInstanceProposals.approve" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  approve</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantQuorumMember">Cloud KMS single-tenant HSM Quorum Member</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantQuorumMember</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.singleTenantHsmInstanceProposals.create" class="permission-name add-link" data-text="cloudkms.singleTenantHsmInstanceProposals.create" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantProposer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.singleTenantHsmInstanceProposals.delete" class="permission-name add-link" data-text="cloudkms.singleTenantHsmInstanceProposals.delete" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantProposer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.singleTenantHsmInstanceProposals.execute" class="permission-name add-link" data-text="cloudkms.singleTenantHsmInstanceProposals.execute" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  execute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantExecutor">Cloud KMS single-tenant HSM Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantExecutor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.singleTenantHsmInstanceProposals.get" class="permission-name add-link" data-text="cloudkms.singleTenantHsmInstanceProposals.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantExecutor">Cloud KMS single-tenant HSM Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantQuorumMember">Cloud KMS single-tenant HSM Quorum Member</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.singleTenantHsmInstanceProposals.list" class="permission-name add-link" data-text="cloudkms.singleTenantHsmInstanceProposals.list" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantExecutor">Cloud KMS single-tenant HSM Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantQuorumMember">Cloud KMS single-tenant HSM Quorum Member</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.singleTenantHsmInstances.create" class="permission-name add-link" data-text="cloudkms.singleTenantHsmInstances.create" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantProposer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.singleTenantHsmInstances.get" class="permission-name add-link" data-text="cloudkms.singleTenantHsmInstances.get" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantExecutor">Cloud KMS single-tenant HSM Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantKeyCreator">Cloud KMS single-tenant HSM Key Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantKeyCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantQuorumMember">Cloud KMS single-tenant HSM Quorum Member</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudkms.singleTenantHsmInstances.list" class="permission-name add-link" data-text="cloudkms.singleTenantHsmInstances.list" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantExecutor">Cloud KMS single-tenant HSM Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantKeyCreator">Cloud KMS single-tenant HSM Key Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantKeyCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantQuorumMember">Cloud KMS single-tenant HSM Quorum Member</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudkms.singleTenantHsmInstances.use" class="permission-name add-link" data-text="cloudkms.singleTenantHsmInstances.use" tabindex="-1"><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantKeyCreator">Cloud KMS single-tenant HSM Key Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.hsmSingleTenantKeyCreator</code> )</p></td>
</tr>
</tbody>
</table>
