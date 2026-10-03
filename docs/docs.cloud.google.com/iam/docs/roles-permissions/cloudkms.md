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
<td>Cloud KMS Admin
<p>( <code>roles/ cloudkms.admin</code> )</p>
<p>Provides access to Cloud KMS resources, except for access to restricted resource types and cryptographic operations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms.autokeyConfigs.*</code></p>
<ul>
<li><code>cloudkms.autokeyConfigs.get</code></li>
<li><code>cloudkms.autokeyConfigs.update</code></li>
</ul>
<p><code>cloudkms. cryptoKeyVersions. create</code></p>
<p><code>cloudkms. cryptoKeyVersions. delete</code></p>
<p><code>cloudkms. cryptoKeyVersions. destroy</code></p>
<p><code>cloudkms.cryptoKeyVersions.get</code></p>
<p><code>cloudkms. cryptoKeyVersions. list</code></p>
<p><code>cloudkms. cryptoKeyVersions. restore</code></p>
<p><code>cloudkms. cryptoKeyVersions. trustedImportExport</code></p>
<p><code>cloudkms. cryptoKeyVersions. update</code></p>
<p><code>cloudkms. cryptoKeyVersions. useToDecryptViaDelegation</code></p>
<p><code>cloudkms. cryptoKeyVersions. useToEncryptViaDelegation</code></p>
<p><code>cloudkms.cryptoKeys.*</code></p>
<ul>
<li><code>cloudkms.cryptoKeys.create</code></li>
<li><code>cloudkms.cryptoKeys.delete</code></li>
<li><code>cloudkms.cryptoKeys.get</code></li>
<li><code>cloudkms. cryptoKeys. getIamPolicy</code></li>
<li><code>cloudkms.cryptoKeys.list</code></li>
<li><code>cloudkms. cryptoKeys. setIamPolicy</code></li>
<li><code>cloudkms.cryptoKeys.update</code></li>
</ul>
<p><code>cloudkms.ekmConfigs.*</code></p>
<ul>
<li><code>cloudkms.ekmConfigs.get</code></li>
<li><code>cloudkms. ekmConfigs. getIamPolicy</code></li>
<li><code>cloudkms. ekmConfigs. setIamPolicy</code></li>
<li><code>cloudkms.ekmConfigs.update</code></li>
</ul>
<p><code>cloudkms.ekmConnections.*</code></p>
<ul>
<li><code>cloudkms.ekmConnections.create</code></li>
<li><code>cloudkms.ekmConnections.get</code></li>
<li><code>cloudkms. ekmConnections. getIamPolicy</code></li>
<li><code>cloudkms.ekmConnections.list</code></li>
<li><code>cloudkms. ekmConnections. setIamPolicy</code></li>
<li><code>cloudkms.ekmConnections.update</code></li>
<li><code>cloudkms.ekmConnections.use</code></li>
<li><code>cloudkms. ekmConnections. verifyConnectivity</code></li>
</ul>
<p><code>cloudkms. folders. showEffectiveAutokeyConfig</code></p>
<p><code>cloudkms.importJobs.*</code></p>
<ul>
<li><code>cloudkms.importJobs.create</code></li>
<li><code>cloudkms.importJobs.delete</code></li>
<li><code>cloudkms.importJobs.get</code></li>
<li><code>cloudkms. importJobs. getIamPolicy</code></li>
<li><code>cloudkms.importJobs.list</code></li>
<li><code>cloudkms. importJobs. setIamPolicy</code></li>
<li><code>cloudkms. importJobs. useToImport</code></li>
</ul>
<p><code>cloudkms.kajPolicyConfigs.*</code></p>
<ul>
<li><code>cloudkms.kajPolicyConfigs.get</code></li>
<li><code>cloudkms. kajPolicyConfigs. update</code></li>
</ul>
<p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.keyRings.*</code></p>
<ul>
<li><code>cloudkms.keyRings.create</code></li>
<li><code>cloudkms. keyRings. createTagBinding</code></li>
<li><code>cloudkms.keyRings.delete</code></li>
<li><code>cloudkms. keyRings. deleteTagBinding</code></li>
<li><code>cloudkms.keyRings.get</code></li>
<li><code>cloudkms.keyRings.getIamPolicy</code></li>
<li><code>cloudkms.keyRings.list</code></li>
<li><code>cloudkms. keyRings. listEffectiveTags</code></li>
<li><code>cloudkms. keyRings. listTagBindings</code></li>
<li><code>cloudkms.keyRings.setIamPolicy</code></li>
</ul>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>cloudkms. locations. optOutKeyDeletionMsa</code></p>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms.projects.*</code></p>
<ul>
<li><code>cloudkms. projects. showEffectiveAutokeyConfig</code></li>
<li><code>cloudkms. projects. showEffectiveKajEnrollmentConfig</code></li>
<li><code>cloudkms. projects. showEffectiveKajPolicyConfig</code></li>
</ul>
<p><code>cloudkms.retiredResources.*</code></p>
<ul>
<li><code>cloudkms.retiredResources.get</code></li>
<li><code>cloudkms.retiredResources.list</code></li>
</ul>
<p><code>cloudkms. singleTenantHsmInstanceProposals. delete</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. get</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. list</code></p>
<p><code>cloudkms. singleTenantHsmInstances.*</code></p>
<ul>
<li><code>cloudkms. singleTenantHsmInstances. create</code></li>
<li><code>cloudkms. singleTenantHsmInstances. get</code></li>
<li><code>cloudkms. singleTenantHsmInstances. list</code></li>
<li><code>cloudkms. singleTenantHsmInstances. use</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS CryptoKey Encrypter/Decrypter
<p>( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypter</code> )</p>
<p>Provides ability to use Cloud KMS resources for encrypt and decrypt operations only.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToDecrypt</code></p>
<p><code>cloudkms. cryptoKeyVersions. useToEncrypt</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS Viewer
<p>( <code>roles/ cloudkms.viewer</code> )</p>
<p>Enables Get and List operations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms.autokeyConfigs.get</code></p>
<p><code>cloudkms.cryptoKeyVersions.get</code></p>
<p><code>cloudkms. cryptoKeyVersions. list</code></p>
<p><code>cloudkms.cryptoKeys.get</code></p>
<p><code>cloudkms.cryptoKeys.list</code></p>
<p><code>cloudkms.ekmConfigs.get</code></p>
<p><code>cloudkms.ekmConnections.get</code></p>
<p><code>cloudkms.ekmConnections.list</code></p>
<p><code>cloudkms. folders. showEffectiveAutokeyConfig</code></p>
<p><code>cloudkms.importJobs.get</code></p>
<p><code>cloudkms.importJobs.list</code></p>
<p><code>cloudkms.kajPolicyConfigs.get</code></p>
<p><code>cloudkms.keyHandles.get</code></p>
<p><code>cloudkms.keyHandles.list</code></p>
<p><code>cloudkms.keyRings.get</code></p>
<p><code>cloudkms.keyRings.list</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>cloudkms. protectableResources. list</code></p>
<p><code>cloudkms.retiredResources.*</code></p>
<ul>
<li><code>cloudkms.retiredResources.get</code></li>
<li><code>cloudkms.retiredResources.list</code></li>
</ul>
<p><code>cloudkms. singleTenantHsmInstanceProposals. get</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. list</code></p>
<p><code>cloudkms. singleTenantHsmInstances. get</code></p>
<p><code>cloudkms. singleTenantHsmInstances. list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS Autokey Admin
<p>( <code>roles/ cloudkms.autokeyAdmin</code> )</p>
<p>Enables management of AutokeyConfig.</p></td>
<td><p><code>cloudkms.autokeyConfigs.*</code></p>
<ul>
<li><code>cloudkms.autokeyConfigs.get</code></li>
<li><code>cloudkms.autokeyConfigs.update</code></li>
</ul>
<p><code>cloudkms. folders. showEffectiveAutokeyConfig</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS Autokey User
<p>( <code>roles/ cloudkms.autokeyUser</code> )</p>
<p>Grants ability to use KeyHandle resources.</p></td>
<td><p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS CryptoKey Decrypter
<p>( <code>roles/ cloudkms.cryptoKeyDecrypter</code> )</p>
<p>Provides ability to use Cloud KMS resources for decrypt operations only.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToDecrypt</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS CryptoKey Decrypter Via Delegation
<p>( <code>roles/ cloudkms.cryptoKeyDecrypterViaDelegation</code> )</p>
<p>Enables Decrypt operations via other Google Cloud services</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToDecryptViaDelegation</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS CryptoKey Encrypter
<p>( <code>roles/ cloudkms.cryptoKeyEncrypter</code> )</p>
<p>Provides ability to use Cloud KMS resources for encrypt operations only.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToEncrypt</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation
<p>( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p>
<p>Enables Encrypt and Decrypt operations via other Google Cloud services</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToDecryptViaDelegation</code></p>
<p><code>cloudkms. cryptoKeyVersions. useToEncryptViaDelegation</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS CryptoKey Encrypter Via Delegation
<p>( <code>roles/ cloudkms.cryptoKeyEncrypterViaDelegation</code> )</p>
<p>Enables Encrypt operations via other Google Cloud services</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToEncryptViaDelegation</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS Crypto Operator
<p>( <code>roles/ cloudkms.cryptoOperator</code> )</p>
<p>Enables all Crypto Operations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToDecapsulate</code></p>
<p><code>cloudkms. cryptoKeyVersions. useToDecrypt</code></p>
<p><code>cloudkms. cryptoKeyVersions. useToEncrypt</code></p>
<p><code>cloudkms. cryptoKeyVersions. useToSign</code></p>
<p><code>cloudkms. cryptoKeyVersions. useToVerify</code></p>
<p><code>cloudkms. cryptoKeyVersions. viewPublicKey</code></p>
<p><code>cloudkms. locations. generateRandomBytes</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS CryptoKey Decapsulator <sup>Beta</sup>
<p>( <code>roles/ cloudkms.decapsulator</code> )</p>
<p>Enables Decapsulate and GetPublicKey operations</p></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToDecapsulate</code></p>
<p><code>cloudkms. cryptoKeyVersions. viewPublicKey</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS EkmConnections Admin
<p>( <code>roles/ cloudkms.ekmConnectionsAdmin</code> )</p>
<p>Enables management of EkmConnections.</p></td>
<td><p><code>cloudkms.ekmConfigs.get</code></p>
<p><code>cloudkms.ekmConfigs.update</code></p>
<p><code>cloudkms.ekmConnections.create</code></p>
<p><code>cloudkms.ekmConnections.get</code></p>
<p><code>cloudkms.ekmConnections.list</code></p>
<p><code>cloudkms.ekmConnections.update</code></p>
<p><code>cloudkms. ekmConnections. verifyConnectivity</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS Encryption Dashboard Viewer
<p>( <code>roles/ cloudkms.encryptionDashboardViewer</code> )</p>
<p>Enables viewing KMS encryption dashboard.</p></td>
<td><p><code>cloudkms.cryptoKeys.list</code></p>
<p><code>cloudkms. protectableResources. list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS Expert PQ Asymmetric Signing Key Manager
<p>( <code>roles/ cloudkms.expertPqcSigner</code> )</p>
<p>Enables PQ asymmetric signing key management.</p></td>
<td><p><code>cloudkms. cryptoKeyVersions. managePqcSign</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS Expert Raw AES-CBC Key Manager
<p>( <code>roles/ cloudkms.expertRawAesCbc</code> )</p>
<p>Enables raw AES-CBC keys management.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. manageRawAesCbcKeys</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS Expert Raw AES-CTR Key Manager
<p>( <code>roles/ cloudkms.expertRawAesCtr</code> )</p>
<p>Enables raw AES-CTR keys management.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. manageRawAesCtrKeys</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS Expert Raw PKCS#1 Key Manager
<p>( <code>roles/ cloudkms.expertRawPKCS1</code> )</p>
<p>Enables raw PKCS#1 keys management.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. manageRawPKCS1Keys</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS single-tenant HSM Executor
<p>( <code>roles/ cloudkms.hsmSingleTenantExecutor</code> )</p>
<p>Grants ability to execute SingleTenantHsmInstanceProposal resources.</p></td>
<td><p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. execute</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. get</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. list</code></p>
<p><code>cloudkms. singleTenantHsmInstances. get</code></p>
<p><code>cloudkms. singleTenantHsmInstances. list</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS single-tenant HSM Key Creator
<p>( <code>roles/ cloudkms.hsmSingleTenantKeyCreator</code> )</p>
<p>Grants ability to use single-tenant HSM instances to create keys. This role must be combined with another role that grants the ability to create cryptoKeys.</p></td>
<td><p><code>cloudkms. singleTenantHsmInstances. get</code></p>
<p><code>cloudkms. singleTenantHsmInstances. list</code></p>
<p><code>cloudkms. singleTenantHsmInstances. use</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS single-tenant HSM Proposer
<p>( <code>roles/ cloudkms.hsmSingleTenantProposer</code> )</p>
<p>Grants ability to create SingleTenantHsmInstances and SingleTenantHsmInstanceProposals.</p></td>
<td><p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. create</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. delete</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. get</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. list</code></p>
<p><code>cloudkms. singleTenantHsmInstances. create</code></p>
<p><code>cloudkms. singleTenantHsmInstances. get</code></p>
<p><code>cloudkms. singleTenantHsmInstances. list</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS single-tenant HSM Quorum Member
<p>( <code>roles/ cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p>Grants ability to approve SingleTenantHsmInstanceProposal resources.</p></td>
<td><p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. approve</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. get</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. list</code></p>
<p><code>cloudkms. singleTenantHsmInstances. get</code></p>
<p><code>cloudkms. singleTenantHsmInstances. list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS Importer
<p>( <code>roles/ cloudkms.importer</code> )</p>
<p>Enables ImportCryptoKeyVersion, CreateImportJob, ListImportJobs, and GetImportJob operations</p></td>
<td><p><code>cloudkms. cryptoKeyVersions. trustedImportExport</code></p>
<p><code>cloudkms.importJobs.create</code></p>
<p><code>cloudkms.importJobs.get</code></p>
<p><code>cloudkms.importJobs.list</code></p>
<p><code>cloudkms. importJobs. useToImport</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td>Key Access Justifications Enrollment Viewer
<p>( <code>roles/ cloudkms.keyAccessJustificationsEnrollmentConfigViewer</code> )</p>
<p>Grant ability to view Key Access Justification enrollment configs of a project.</p></td>
<td><p><code>cloudkms. projects. showEffectiveKajEnrollmentConfig</code></p></td>
</tr>
<tr class="odd">
<td>Key Access Justifications Policy Config Admin
<p>( <code>roles/ cloudkms.keyAccessJustificationsPolicyConfigAdmin</code> )</p>
<p>Grant ability to manage Key Access Justifications Policy at parent resource level.</p></td>
<td><p><code>cloudkms.kajPolicyConfigs.*</code></p>
<ul>
<li><code>cloudkms.kajPolicyConfigs.get</code></li>
<li><code>cloudkms. kajPolicyConfigs. update</code></li>
</ul>
<p><code>cloudkms. projects. showEffectiveKajPolicyConfig</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS Protected Resources Viewer
<p>( <code>roles/ cloudkms.protectedResourcesViewer</code> )</p>
<p>Enables viewing protected resources.</p></td>
<td><p><code>cloudkms. protectedResources. search</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS CryptoKey Public Key Viewer
<p>( <code>roles/ cloudkms.publicKeyViewer</code> )</p>
<p>Enables GetPublicKey operations</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. viewPublicKey</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS CryptoKey Signer
<p>( <code>roles/ cloudkms.signer</code> )</p>
<p>Enables Sign operations</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToSign</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS CryptoKey Signer/Verifier
<p>( <code>roles/ cloudkms.signerVerifier</code> )</p>
<p>Enables Sign, Verify, and GetPublicKey operations</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToSign</code></p>
<p><code>cloudkms. cryptoKeyVersions. useToVerify</code></p>
<p><code>cloudkms. cryptoKeyVersions. viewPublicKey</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS CryptoKey Verifier
<p>( <code>roles/ cloudkms.verifier</code> )</p>
<p>Enables Verify and GetPublicKey operations</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>CryptoKey</li>
</ul></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToVerify</code></p>
<p><code>cloudkms. cryptoKeyVersions. viewPublicKey</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
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
<td>Cloud KMS Organization Service Agent
<p>( <code>roles/ cloudkms.orgServiceAgent</code> )</p>
<p>Gives Cloud KMS organization-level service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudasset.assets.listResource</code></p>
<p><code>cloudasset. assets. searchAllIamPolicies</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p></td>
</tr>
<tr class="even">
<td>Cloud KMS Service Agent
<p>( <code>roles/ cloudkms.serviceAgent</code> )</p>
<p>Gives Cloud KMS service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudasset. assets. listCloudkmsCryptoKeys</code></p>
<p><code>cloudasset.assets.listResource</code></p>
<p><code>cloudasset. assets. searchAllIamPolicies</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudkms.cryptoKeys.create</code></p>
<p><code>cloudkms. cryptoKeys. getIamPolicy</code></p>
<p><code>cloudkms. cryptoKeys. setIamPolicy</code></p>
<p><code>cloudkms.keyRings.create</code></p>
<p><code>cloudkms.keyRings.get</code></p></td>
</tr>
<tr class="odd">
<td>Cloud KMS KACLS Service Agent
<p>( <code>roles/ cloudkmskacls.serviceAgent</code> )</p>
<p>Grants Cloud KMS KACLS Service Agent access to KMS resource permissions to perform DEK encryption/decryption.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToDecrypt</code></p>
<p><code>cloudkms. cryptoKeyVersions. useToEncrypt</code></p>
<p><code>cloudkms.cryptoKeys.get</code></p></td>
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
<td><code>cloudkms.autokeyConfigs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyAdmin">Cloud KMS Autokey Admin</a> ( <code>roles/ cloudkms.autokeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms.autokeyConfigs.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyAdmin">Cloud KMS Autokey Admin</a> ( <code>roles/ cloudkms.autokeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. cryptoKeyVersions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. cryptoKeyVersions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. cryptoKeyVersions. destroy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms.cryptoKeyVersions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code>roles/ container.cloudKmsKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. cryptoKeyVersions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. cryptoKeyVersions. managePqcSign</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertPqcSigner">Cloud KMS Expert PQ Asymmetric Signing Key Manager</a> ( <code>roles/ cloudkms.expertPqcSigner</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. cryptoKeyVersions. manageRawAesCbcKeys</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCbc">Cloud KMS Expert Raw AES-CBC Key Manager</a> ( <code>roles/ cloudkms.expertRawAesCbc</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. cryptoKeyVersions. manageRawAesCtrKeys</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCtr">Cloud KMS Expert Raw AES-CTR Key Manager</a> ( <code>roles/ cloudkms.expertRawAesCtr</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. cryptoKeyVersions. manageRawPKCS1Keys</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawPKCS1">Cloud KMS Expert Raw PKCS#1 Key Manager</a> ( <code>roles/ cloudkms.expertRawPKCS1</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. cryptoKeyVersions. restore</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. cryptoKeyVersions. trustedImportExport</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code>roles/ cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. cryptoKeyVersions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. cryptoKeyVersions. useToDecapsulate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code>roles/ cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.decapsulator">Cloud KMS CryptoKey Decapsulator</a> ( <code>roles/ cloudkms.decapsulator</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. cryptoKeyVersions. useToDecrypt</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypter">Cloud KMS CryptoKey Encrypter/Decrypter</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypter">Cloud KMS CryptoKey Decrypter</a> ( <code>roles/ cloudkms.cryptoKeyDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code>roles/ cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkmskacls.serviceAgent">Cloud KMS KACLS Service Agent</a> ( <code>roles/ cloudkmskacls.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>cloudkms. cryptoKeyVersions. useToDecryptViaDelegation</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypterViaDelegation">Cloud KMS CryptoKey Decrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypterViaDelegation">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. cryptoKeyVersions. useToEncrypt</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypter">Cloud KMS CryptoKey Encrypter/Decrypter</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypter">Cloud KMS CryptoKey Encrypter</a> ( <code>roles/ cloudkms.cryptoKeyEncrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code>roles/ cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkmskacls.serviceAgent">Cloud KMS KACLS Service Agent</a> ( <code>roles/ cloudkmskacls.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>cloudkms. cryptoKeyVersions. useToEncryptViaDelegation</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypterViaDelegation">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterViaDelegation">Cloud KMS CryptoKey Encrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterViaDelegation</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. cryptoKeyVersions. useToSign</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code>roles/ cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signer">Cloud KMS CryptoKey Signer</a> ( <code>roles/ cloudkms.signer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signerVerifier">Cloud KMS CryptoKey Signer/Verifier</a> ( <code>roles/ cloudkms.signerVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code>roles/ container.cloudKmsKeyUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. cryptoKeyVersions. useToVerify</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code>roles/ cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signerVerifier">Cloud KMS CryptoKey Signer/Verifier</a> ( <code>roles/ cloudkms.signerVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.verifier">Cloud KMS CryptoKey Verifier</a> ( <code>roles/ cloudkms.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code>roles/ container.cloudKmsKeyUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. cryptoKeyVersions. viewPublicKey</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code>roles/ cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.decapsulator">Cloud KMS CryptoKey Decapsulator</a> ( <code>roles/ cloudkms.decapsulator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.publicKeyViewer">Cloud KMS CryptoKey Public Key Viewer</a> ( <code>roles/ cloudkms.publicKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signerVerifier">Cloud KMS CryptoKey Signer/Verifier</a> ( <code>roles/ cloudkms.signerVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.verifier">Cloud KMS CryptoKey Verifier</a> ( <code>roles/ cloudkms.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code>roles/ container.cloudKmsKeyUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.cryptoKeys.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.serviceAgent">Cloud KMS Service Agent</a> ( <code>roles/ cloudkms.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudkms.cryptoKeys.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.cryptoKeys.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code>roles/ container.cloudKmsKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkmskacls.serviceAgent">Cloud KMS KACLS Service Agent</a> ( <code>roles/ cloudkmskacls.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudkms. cryptoKeys. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.serviceAgent">Cloud KMS Service Agent</a> ( <code>roles/ cloudkms.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>cloudkms.cryptoKeys.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.encryptionDashboardViewer">Cloud KMS Encryption Dashboard Viewer</a> ( <code>roles/ cloudkms.encryptionDashboardViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudkms. cryptoKeys. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.serviceAgent">Cloud KMS Service Agent</a> ( <code>roles/ cloudkms.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>cloudkms.cryptoKeys.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms.ekmConfigs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code>roles/ cloudkms.ekmConnectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. ekmConfigs. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. ekmConfigs. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.ekmConfigs.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code>roles/ cloudkms.ekmConnectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms.ekmConnections.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code>roles/ cloudkms.ekmConnectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.ekmConnections.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code>roles/ cloudkms.ekmConnectionsAdmin</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.ekmServiceAgent">Cloud Controls Partner EKM Service Agent</a> ( <code>roles/ cloudcontrolspartner.ekmServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudkms. ekmConnections. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.ekmServiceAgent">Cloud Controls Partner EKM Service Agent</a> ( <code>roles/ cloudcontrolspartner.ekmServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>cloudkms.ekmConnections.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code>roles/ cloudkms.ekmConnectionsAdmin</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.ekmServiceAgent">Cloud Controls Partner EKM Service Agent</a> ( <code>roles/ cloudcontrolspartner.ekmServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudkms. ekmConnections. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.ekmConnections.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code>roles/ cloudkms.ekmConnectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms.ekmConnections.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. ekmConnections. verifyConnectivity</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code>roles/ cloudkms.ekmConnectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.ekmServiceAgent">Cloud Controls Partner EKM Service Agent</a> ( <code>roles/ cloudcontrolspartner.ekmServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudkms. folders. showEffectiveAutokeyConfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyAdmin">Cloud KMS Autokey Admin</a> ( <code>roles/ cloudkms.autokeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.importJobs.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code>roles/ cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms.importJobs.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.importJobs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code>roles/ cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. importJobs. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.importJobs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code>roles/ cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. importJobs. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. importJobs. useToImport</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code>roles/ cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms.kajPolicyConfigs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.keyAccessJustificationsPolicyConfigAdmin">Key Access Justifications Policy Config Admin</a> ( <code>roles/ cloudkms.keyAccessJustificationsPolicyConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. kajPolicyConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.keyAccessJustificationsPolicyConfigAdmin">Key Access Justifications Policy Config Admin</a> ( <code>roles/ cloudkms.keyAccessJustificationsPolicyConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms.keyHandles.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.editor">Apigee Editor</a> ( <code>roles/ apigee.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code>roles/ artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code>roles/ bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.admin">Kubernetes Engine Admin</a> ( <code>roles/ container.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterAdmin">Kubernetes Engine Cluster Admin</a> ( <code>roles/ container.clusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code>roles/ dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code>roles/ dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code>roles/ datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.admin">Memorystore Admin</a> ( <code>roles/ memorystore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code>roles/ redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code>roles/ secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code>roles/ spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code>roles/ vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code>roles/ workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyUser">Cloud KMS Autokey User</a> ( <code>roles/ cloudkms.autokeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code>roles/ dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code>roles/ spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.keyHandles.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.editor">Apigee Editor</a> ( <code>roles/ apigee.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code>roles/ artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code>roles/ bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.admin">Kubernetes Engine Admin</a> ( <code>roles/ container.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterAdmin">Kubernetes Engine Cluster Admin</a> ( <code>roles/ container.clusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code>roles/ dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code>roles/ dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code>roles/ datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.admin">Memorystore Admin</a> ( <code>roles/ memorystore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code>roles/ redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code>roles/ secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code>roles/ spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code>roles/ vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code>roles/ workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyUser">Cloud KMS Autokey User</a> ( <code>roles/ cloudkms.autokeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code>roles/ dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code>roles/ spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms.keyHandles.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.editor">Apigee Editor</a> ( <code>roles/ apigee.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code>roles/ artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code>roles/ bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.admin">Kubernetes Engine Admin</a> ( <code>roles/ container.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterAdmin">Kubernetes Engine Cluster Admin</a> ( <code>roles/ container.clusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code>roles/ dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code>roles/ dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code>roles/ datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.admin">Memorystore Admin</a> ( <code>roles/ memorystore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code>roles/ redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code>roles/ secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code>roles/ spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code>roles/ vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code>roles/ workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyUser">Cloud KMS Autokey User</a> ( <code>roles/ cloudkms.autokeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code>roles/ dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code>roles/ spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.keyRings.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.serviceAgent">Cloud KMS Service Agent</a> ( <code>roles/ cloudkms.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudkms. keyRings. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.keyRings.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. keyRings. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.keyRings.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.serviceAgent">Cloud KMS Service Agent</a> ( <code>roles/ cloudkms.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudkms.keyRings.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.keyRings.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudkms. keyRings. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
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
<td><code>cloudkms. keyRings. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
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
<td><code>cloudkms.keyRings.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. locations. generateRandomBytes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code>roles/ cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypter">Cloud KMS CryptoKey Encrypter/Decrypter</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypter">Cloud KMS CryptoKey Decrypter</a> ( <code>roles/ cloudkms.cryptoKeyDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypterViaDelegation">Cloud KMS CryptoKey Decrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypter">Cloud KMS CryptoKey Encrypter</a> ( <code>roles/ cloudkms.cryptoKeyEncrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypterViaDelegation">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterViaDelegation">Cloud KMS CryptoKey Encrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code>roles/ cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.decapsulator">Cloud KMS CryptoKey Decapsulator</a> ( <code>roles/ cloudkms.decapsulator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertPqcSigner">Cloud KMS Expert PQ Asymmetric Signing Key Manager</a> ( <code>roles/ cloudkms.expertPqcSigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCbc">Cloud KMS Expert Raw AES-CBC Key Manager</a> ( <code>roles/ cloudkms.expertRawAesCbc</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCtr">Cloud KMS Expert Raw AES-CTR Key Manager</a> ( <code>roles/ cloudkms.expertRawAesCtr</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawPKCS1">Cloud KMS Expert Raw PKCS#1 Key Manager</a> ( <code>roles/ cloudkms.expertRawPKCS1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code>roles/ cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.publicKeyViewer">Cloud KMS CryptoKey Public Key Viewer</a> ( <code>roles/ cloudkms.publicKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signer">Cloud KMS CryptoKey Signer</a> ( <code>roles/ cloudkms.signer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signerVerifier">Cloud KMS CryptoKey Signer/Verifier</a> ( <code>roles/ cloudkms.signerVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.verifier">Cloud KMS CryptoKey Verifier</a> ( <code>roles/ cloudkms.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code>roles/ container.cloudKmsKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>cloudkms.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypter">Cloud KMS CryptoKey Encrypter/Decrypter</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypter">Cloud KMS CryptoKey Decrypter</a> ( <code>roles/ cloudkms.cryptoKeyDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypterViaDelegation">Cloud KMS CryptoKey Decrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypter">Cloud KMS CryptoKey Encrypter</a> ( <code>roles/ cloudkms.cryptoKeyEncrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypterViaDelegation">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterViaDelegation">Cloud KMS CryptoKey Encrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code>roles/ cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.decapsulator">Cloud KMS CryptoKey Decapsulator</a> ( <code>roles/ cloudkms.decapsulator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertPqcSigner">Cloud KMS Expert PQ Asymmetric Signing Key Manager</a> ( <code>roles/ cloudkms.expertPqcSigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCbc">Cloud KMS Expert Raw AES-CBC Key Manager</a> ( <code>roles/ cloudkms.expertRawAesCbc</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCtr">Cloud KMS Expert Raw AES-CTR Key Manager</a> ( <code>roles/ cloudkms.expertRawAesCtr</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawPKCS1">Cloud KMS Expert Raw PKCS#1 Key Manager</a> ( <code>roles/ cloudkms.expertRawPKCS1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code>roles/ cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.publicKeyViewer">Cloud KMS CryptoKey Public Key Viewer</a> ( <code>roles/ cloudkms.publicKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signer">Cloud KMS CryptoKey Signer</a> ( <code>roles/ cloudkms.signer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signerVerifier">Cloud KMS CryptoKey Signer/Verifier</a> ( <code>roles/ cloudkms.signerVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.verifier">Cloud KMS CryptoKey Verifier</a> ( <code>roles/ cloudkms.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code>roles/ container.cloudKmsKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudkms. locations. optOutKeyDeletionMsa</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.editor">Apigee Editor</a> ( <code>roles/ apigee.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code>roles/ artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code>roles/ bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.admin">Kubernetes Engine Admin</a> ( <code>roles/ container.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterAdmin">Kubernetes Engine Cluster Admin</a> ( <code>roles/ container.clusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code>roles/ dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code>roles/ dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code>roles/ datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.admin">Memorystore Admin</a> ( <code>roles/ memorystore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code>roles/ redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code>roles/ secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code>roles/ spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code>roles/ vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code>roles/ workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyUser">Cloud KMS Autokey User</a> ( <code>roles/ cloudkms.autokeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantExecutor">Cloud KMS single-tenant HSM Executor</a> ( <code>roles/ cloudkms.hsmSingleTenantExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code>roles/ cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantQuorumMember">Cloud KMS single-tenant HSM Quorum Member</a> ( <code>roles/ cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code>roles/ dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code>roles/ spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. projects. showEffectiveAutokeyConfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.editor">Apigee Editor</a> ( <code>roles/ apigee.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code>roles/ artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code>roles/ bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.admin">Kubernetes Engine Admin</a> ( <code>roles/ container.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterAdmin">Kubernetes Engine Cluster Admin</a> ( <code>roles/ container.clusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code>roles/ dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code>roles/ dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code>roles/ datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.admin">Memorystore Admin</a> ( <code>roles/ memorystore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code>roles/ redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code>roles/ secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code>roles/ spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code>roles/ vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code>roles/ workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyAdmin">Cloud KMS Autokey Admin</a> ( <code>roles/ cloudkms.autokeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.autokeyUser">Cloud KMS Autokey User</a> ( <code>roles/ cloudkms.autokeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code>roles/ dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code>roles/ spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. projects. showEffectiveKajEnrollmentConfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.keyAccessJustificationsEnrollmentConfigViewer">Key Access Justifications Enrollment Viewer</a> ( <code>roles/ cloudkms.keyAccessJustificationsEnrollmentConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. projects. showEffectiveKajPolicyConfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.keyAccessJustificationsPolicyConfigAdmin">Key Access Justifications Policy Config Admin</a> ( <code>roles/ cloudkms.keyAccessJustificationsPolicyConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. protectableResources. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.encryptionDashboardViewer">Cloud KMS Encryption Dashboard Viewer</a> ( <code>roles/ cloudkms.encryptionDashboardViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. protectedResources. search</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.protectedResourcesViewer">Cloud KMS Protected Resources Viewer</a> ( <code>roles/ cloudkms.protectedResourcesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms.retiredResources.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms.retiredResources.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. singleTenantHsmInstanceProposals. approve</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantQuorumMember">Cloud KMS single-tenant HSM Quorum Member</a> ( <code>roles/ cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. singleTenantHsmInstanceProposals. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code>roles/ cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. singleTenantHsmInstanceProposals. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code>roles/ cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. singleTenantHsmInstanceProposals. execute</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantExecutor">Cloud KMS single-tenant HSM Executor</a> ( <code>roles/ cloudkms.hsmSingleTenantExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. singleTenantHsmInstanceProposals. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantExecutor">Cloud KMS single-tenant HSM Executor</a> ( <code>roles/ cloudkms.hsmSingleTenantExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code>roles/ cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantQuorumMember">Cloud KMS single-tenant HSM Quorum Member</a> ( <code>roles/ cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. singleTenantHsmInstanceProposals. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantExecutor">Cloud KMS single-tenant HSM Executor</a> ( <code>roles/ cloudkms.hsmSingleTenantExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code>roles/ cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantQuorumMember">Cloud KMS single-tenant HSM Quorum Member</a> ( <code>roles/ cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. singleTenantHsmInstances. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code>roles/ cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. singleTenantHsmInstances. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantExecutor">Cloud KMS single-tenant HSM Executor</a> ( <code>roles/ cloudkms.hsmSingleTenantExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantKeyCreator">Cloud KMS single-tenant HSM Key Creator</a> ( <code>roles/ cloudkms.hsmSingleTenantKeyCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code>roles/ cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantQuorumMember">Cloud KMS single-tenant HSM Quorum Member</a> ( <code>roles/ cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudkms. singleTenantHsmInstances. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantExecutor">Cloud KMS single-tenant HSM Executor</a> ( <code>roles/ cloudkms.hsmSingleTenantExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantKeyCreator">Cloud KMS single-tenant HSM Key Creator</a> ( <code>roles/ cloudkms.hsmSingleTenantKeyCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantProposer">Cloud KMS single-tenant HSM Proposer</a> ( <code>roles/ cloudkms.hsmSingleTenantProposer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantQuorumMember">Cloud KMS single-tenant HSM Quorum Member</a> ( <code>roles/ cloudkms.hsmSingleTenantQuorumMember</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudkms. singleTenantHsmInstances. use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.hsmSingleTenantKeyCreator">Cloud KMS single-tenant HSM Key Creator</a> ( <code>roles/ cloudkms.hsmSingleTenantKeyCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
