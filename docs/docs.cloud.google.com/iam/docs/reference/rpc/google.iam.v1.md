---
name: documents/docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1
uri: https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1
title: Package google.iam.v1
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

  - `  WorkloadIdentityPools  ` (interface)
  - `  AddAttestationRuleMetadata  ` (message)
  - `  AddAttestationRuleRequest  ` (message)
  - `  AddAttestationRuleResponse  ` (message)
  - `  AttestationRule  ` (message)
  - `  AuditConfig  ` (message)
  - `  AuditLogConfig  ` (message)
  - `  AuditLogConfig.LogType  ` (enum)
  - `  Binding  ` (message)
  - `  BindingDelta  ` (message)
  - `  BindingDelta.Action  ` (enum)
  - `  CreateWorkloadIdentityPoolManagedIdentityRequest  ` (message)
  - `  CreateWorkloadIdentityPoolNamespaceRequest  ` (message)
  - `  CreateWorkloadIdentityPoolProviderKeyRequest  ` (message)
  - `  CreateWorkloadIdentityPoolProviderRequest  ` (message)
  - `  CreateWorkloadIdentityPoolRequest  ` (message)
  - `  DeleteWorkloadIdentityPoolManagedIdentityRequest  ` (message)
  - `  DeleteWorkloadIdentityPoolNamespaceRequest  ` (message)
  - `  DeleteWorkloadIdentityPoolProviderKeyRequest  ` (message)
  - `  DeleteWorkloadIdentityPoolProviderRequest  ` (message)
  - `  DeleteWorkloadIdentityPoolRequest  ` (message)
  - `  GetIamPolicyRequest  ` (message)
  - `  GetPolicyOptions  ` (message)
  - `  GetWorkloadIdentityPoolManagedIdentityRequest  ` (message)
  - `  GetWorkloadIdentityPoolNamespaceRequest  ` (message)
  - `  GetWorkloadIdentityPoolProviderKeyRequest  ` (message)
  - `  GetWorkloadIdentityPoolProviderRequest  ` (message)
  - `  GetWorkloadIdentityPoolRequest  ` (message)
  - `  ListAttestationRulesRequest  ` (message)
  - `  ListAttestationRulesResponse  ` (message)
  - `  ListWorkloadIdentityPoolManagedIdentitiesRequest  ` (message)
  - `  ListWorkloadIdentityPoolManagedIdentitiesResponse  ` (message)
  - `  ListWorkloadIdentityPoolNamespacesRequest  ` (message)
  - `  ListWorkloadIdentityPoolNamespacesResponse  ` (message)
  - `  ListWorkloadIdentityPoolProviderKeysRequest  ` (message)
  - `  ListWorkloadIdentityPoolProviderKeysResponse  ` (message)
  - `  ListWorkloadIdentityPoolProvidersRequest  ` (message)
  - `  ListWorkloadIdentityPoolProvidersResponse  ` (message)
  - `  ListWorkloadIdentityPoolsRequest  ` (message)
  - `  ListWorkloadIdentityPoolsResponse  ` (message)
  - `  Policy  ` (message)
  - `  PolicyDelta  ` (message)
  - `  RemoveAttestationRuleMetadata  ` (message)
  - `  RemoveAttestationRuleRequest  ` (message)
  - `  RemoveAttestationRuleResponse  ` (message)
  - `  SetAttestationRulesMetadata  ` (message)
  - `  SetAttestationRulesRequest  ` (message)
  - `  SetAttestationRulesResponse  ` (message)
  - `  SetIamPolicyRequest  ` (message)
  - `  TestIamPermissionsRequest  ` (message)
  - `  TestIamPermissionsResponse  ` (message)
  - `  TrustStore  ` (message)
  - `  TrustStore.IntermediateCA  ` (message)
  - `  TrustStore.TrustAnchor  ` (message)
  - `  UndeleteWorkloadIdentityPoolManagedIdentityRequest  ` (message)
  - `  UndeleteWorkloadIdentityPoolNamespaceRequest  ` (message)
  - `  UndeleteWorkloadIdentityPoolProviderKeyRequest  ` (message)
  - `  UndeleteWorkloadIdentityPoolProviderRequest  ` (message)
  - `  UndeleteWorkloadIdentityPoolRequest  ` (message)
  - `  UpdateWorkloadIdentityPoolManagedIdentityRequest  ` (message)
  - `  UpdateWorkloadIdentityPoolNamespaceRequest  ` (message)
  - `  UpdateWorkloadIdentityPoolProviderRequest  ` (message)
  - `  UpdateWorkloadIdentityPoolRequest  ` (message)
  - `  WorkloadIdentityPool  ` (message)
  - `  WorkloadIdentityPool.InlineCertificateIssuanceConfig  ` (message)
  - `  WorkloadIdentityPool.InlineCertificateIssuanceConfig.KeyAlgorithm  ` (enum)
  - `  WorkloadIdentityPool.InlineTrustConfig  ` (message)
  - `  WorkloadIdentityPool.Mode  ` (enum)
  - `  WorkloadIdentityPool.State  ` (enum)
  - `  WorkloadIdentityPoolManagedIdentity  ` (message)
  - `  WorkloadIdentityPoolManagedIdentity.State  ` (enum)
  - `  WorkloadIdentityPoolManagedIdentityOperationMetadata  ` (message)
  - `  WorkloadIdentityPoolNamespace  ` (message)
  - `  WorkloadIdentityPoolNamespace.OwnerService  ` (message)
  - `  WorkloadIdentityPoolNamespace.State  ` (enum)
  - `  WorkloadIdentityPoolNamespaceOperationMetadata  ` (message)
  - `  WorkloadIdentityPoolOperationMetadata  ` (message)
  - `  WorkloadIdentityPoolProvider  ` (message)
  - `  WorkloadIdentityPoolProvider.Aws  ` (message)
  - `  WorkloadIdentityPoolProvider.Oidc  ` (message)
  - `  WorkloadIdentityPoolProvider.Saml  ` (message)
  - `  WorkloadIdentityPoolProvider.State  ` (enum)
  - `  WorkloadIdentityPoolProvider.X509  ` (message)
  - `  WorkloadIdentityPoolProviderKey  ` (message)
  - `  WorkloadIdentityPoolProviderKey.KeyUse  ` (enum)
  - `  WorkloadIdentityPoolProviderKey.State  ` (enum)
  - `  WorkloadIdentityPoolProviderKeyOperationMetadata  ` (message)
  - `  WorkloadIdentityPoolProviderOperationMetadata  ` (message)

## WorkloadIdentityPools

Manages WorkloadIdentityPools.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>AddAttestationRule</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc AddAttestationRule(              AddAttestationRuleRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Add an <code dir="ltr" translate="no">            AttestationRule           </code> on a <code dir="ltr" translate="no">            WorkloadIdentityPoolManagedIdentity           </code> .</p>
<p>The total attestation rules after addition must not exceed 50.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">resource</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">CALLBACK</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreateWorkloadIdentityPool</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateWorkloadIdentityPool(              CreateWorkloadIdentityPoolRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Creates a new <code dir="ltr" translate="no">            WorkloadIdentityPool           </code> .</p>
<p>You cannot reuse the name of a deleted pool until 30 days after deletion.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">parent</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.workloadIdentityPools.create</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreateWorkloadIdentityPoolManagedIdentity</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateWorkloadIdentityPoolManagedIdentity(              CreateWorkloadIdentityPoolManagedIdentityRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Creates a new <code dir="ltr" translate="no">            WorkloadIdentityPoolManagedIdentity           </code> in a <code dir="ltr" translate="no">            WorkloadIdentityPoolNamespace           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreateWorkloadIdentityPoolNamespace</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateWorkloadIdentityPoolNamespace(              CreateWorkloadIdentityPoolNamespaceRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Creates a new <code dir="ltr" translate="no">            WorkloadIdentityPoolNamespace           </code> in a <code dir="ltr" translate="no">            WorkloadIdentityPool           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreateWorkloadIdentityPoolProvider</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateWorkloadIdentityPoolProvider(              CreateWorkloadIdentityPoolProviderRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Creates a new <code dir="ltr" translate="no">            WorkloadIdentityPoolProvider           </code> in a <code dir="ltr" translate="no">            WorkloadIdentityPool           </code> .</p>
<p>You cannot reuse the name of a deleted provider until 30 days after deletion.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">parent</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.workloadIdentityPoolProviders.create</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreateWorkloadIdentityPoolProviderKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateWorkloadIdentityPoolProviderKey(              CreateWorkloadIdentityPoolProviderKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Create a new <code dir="ltr" translate="no">            WorkloadIdentityPoolProviderKey           </code> in a <code dir="ltr" translate="no">            WorkloadIdentityPoolProvider           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>DeleteWorkloadIdentityPool</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteWorkloadIdentityPool(              DeleteWorkloadIdentityPoolRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes a <code dir="ltr" translate="no">            WorkloadIdentityPool           </code> .</p>
<p>You cannot use a deleted pool to exchange external credentials for Google Cloud credentials. However, deletion does not revoke credentials that have already been issued. Credentials issued for a deleted pool do not grant access to resources. If the pool is undeleted, and the credentials are not expired, they grant access again. You can undelete a pool for 30 days. After 30 days, deletion is permanent. You cannot update deleted pools. However, you can view and list them.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.workloadIdentityPools.delete</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>DeleteWorkloadIdentityPoolManagedIdentity</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteWorkloadIdentityPoolManagedIdentity(              DeleteWorkloadIdentityPoolManagedIdentityRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes a <code dir="ltr" translate="no">            WorkloadIdentityPoolManagedIdentity           </code> . You can undelete a managed identity for 30 days. After 30 days, deletion is permanent.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>DeleteWorkloadIdentityPoolNamespace</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteWorkloadIdentityPoolNamespace(              DeleteWorkloadIdentityPoolNamespaceRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes a <code dir="ltr" translate="no">            WorkloadIdentityPoolNamespace           </code> . You can undelete a namespace for 30 days. After 30 days, deletion is permanent.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>DeleteWorkloadIdentityPoolProvider</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteWorkloadIdentityPoolProvider(              DeleteWorkloadIdentityPoolProviderRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes a <code dir="ltr" translate="no">            WorkloadIdentityPoolProvider           </code> . Deleting a provider does not revoke credentials that have already been issued; they continue to grant access. You can undelete a provider for 30 days. After 30 days, deletion is permanent. You cannot update deleted providers. However, you can view and list them.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.workloadIdentityPoolProviders.delete</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>DeleteWorkloadIdentityPoolProviderKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteWorkloadIdentityPoolProviderKey(              DeleteWorkloadIdentityPoolProviderKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes an <code dir="ltr" translate="no">            WorkloadIdentityPoolProviderKey           </code> . You can undelete a key for 30 days. After 30 days, deletion is permanent.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>GetIamPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetIamPolicy(              GetIamPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Policy            </code> )</p>
<p>Gets the IAM policy of a <code dir="ltr" translate="no">            WorkloadIdentityPool           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">resource</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">CALLBACK</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>GetWorkloadIdentityPool</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetWorkloadIdentityPool(              GetWorkloadIdentityPoolRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkloadIdentityPool            </code> )</p>
<p>Gets an individual <code dir="ltr" translate="no">            WorkloadIdentityPool           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.workloadIdentityPools.get</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>GetWorkloadIdentityPoolManagedIdentity</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetWorkloadIdentityPoolManagedIdentity(              GetWorkloadIdentityPoolManagedIdentityRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkloadIdentityPoolManagedIdentity            </code> )</p>
<p>Gets an individual <code dir="ltr" translate="no">            WorkloadIdentityPoolManagedIdentity           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>GetWorkloadIdentityPoolNamespace</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetWorkloadIdentityPoolNamespace(              GetWorkloadIdentityPoolNamespaceRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkloadIdentityPoolNamespace            </code> )</p>
<p>Gets an individual <code dir="ltr" translate="no">            WorkloadIdentityPoolNamespace           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>GetWorkloadIdentityPoolProvider</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetWorkloadIdentityPoolProvider(              GetWorkloadIdentityPoolProviderRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkloadIdentityPoolProvider            </code> )</p>
<p>Gets an individual <code dir="ltr" translate="no">            WorkloadIdentityPoolProvider           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.workloadIdentityPoolProviders.get</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>GetWorkloadIdentityPoolProviderKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetWorkloadIdentityPoolProviderKey(              GetWorkloadIdentityPoolProviderKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkloadIdentityPoolProviderKey            </code> )</p>
<p>Gets an individual <code dir="ltr" translate="no">            WorkloadIdentityPoolProviderKey           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>ListAttestationRules</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListAttestationRules(              ListAttestationRulesRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListAttestationRulesResponse            </code> )</p>
<p>List all <code dir="ltr" translate="no">            AttestationRule           </code> on a <code dir="ltr" translate="no">            WorkloadIdentityPoolManagedIdentity           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">resource</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">CALLBACK</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>ListWorkloadIdentityPoolManagedIdentities</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListWorkloadIdentityPoolManagedIdentities(              ListWorkloadIdentityPoolManagedIdentitiesRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListWorkloadIdentityPoolManagedIdentitiesResponse            </code> )</p>
<p>Lists all non-deleted <code dir="ltr" translate="no">            WorkloadIdentityPoolManagedIdentity           </code> s in a namespace. If <code dir="ltr" translate="no">show_deleted</code> is set to <code dir="ltr" translate="no">true</code> , then deleted managed identities are also listed.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>ListWorkloadIdentityPoolNamespaces</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListWorkloadIdentityPoolNamespaces(              ListWorkloadIdentityPoolNamespacesRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListWorkloadIdentityPoolNamespacesResponse            </code> )</p>
<p>Lists all non-deleted <code dir="ltr" translate="no">            WorkloadIdentityPoolNamespace           </code> s in a workload identity pool. If <code dir="ltr" translate="no">show_deleted</code> is set to <code dir="ltr" translate="no">true</code> , then deleted namespaces are also listed.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>ListWorkloadIdentityPoolProviderKeys</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListWorkloadIdentityPoolProviderKeys(              ListWorkloadIdentityPoolProviderKeysRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListWorkloadIdentityPoolProviderKeysResponse            </code> )</p>
<p>Lists all non-deleted <code dir="ltr" translate="no">            WorkloadIdentityPoolProviderKey           </code> s in a project. If <code dir="ltr" translate="no">            show_deleted           </code> is set to <code dir="ltr" translate="no">true</code> , then deleted pools are also listed.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>ListWorkloadIdentityPoolProviders</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListWorkloadIdentityPoolProviders(              ListWorkloadIdentityPoolProvidersRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListWorkloadIdentityPoolProvidersResponse            </code> )</p>
<p>Lists all non-deleted <code dir="ltr" translate="no">            WorkloadIdentityPoolProvider           </code> s in a <code dir="ltr" translate="no">            WorkloadIdentityPool           </code> . If <code dir="ltr" translate="no">show_deleted</code> is set to <code dir="ltr" translate="no">true</code> , then deleted providers are also listed.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">parent</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.workloadIdentityPoolProviders.list</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>ListWorkloadIdentityPools</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListWorkloadIdentityPools(              ListWorkloadIdentityPoolsRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListWorkloadIdentityPoolsResponse            </code> )</p>
<p>Lists all non-deleted <code dir="ltr" translate="no">            WorkloadIdentityPool           </code> s in a project. If <code dir="ltr" translate="no">show_deleted</code> is set to <code dir="ltr" translate="no">true</code> , then deleted pools are also listed.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">parent</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.workloadIdentityPools.list</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>RemoveAttestationRule</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc RemoveAttestationRule(              RemoveAttestationRuleRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Remove an <code dir="ltr" translate="no">            AttestationRule           </code> on a <code dir="ltr" translate="no">            WorkloadIdentityPoolManagedIdentity           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">resource</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">CALLBACK</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>SetAttestationRules</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc SetAttestationRules(              SetAttestationRulesRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Set all <code dir="ltr" translate="no">            AttestationRule           </code> on a <code dir="ltr" translate="no">            WorkloadIdentityPoolManagedIdentity           </code> .</p>
<p>A maximum of 50 AttestationRules can be set.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">resource</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">CALLBACK</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>SetIamPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc SetIamPolicy(              SetIamPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Policy            </code> )</p>
<p>Sets the IAM policies on a <code dir="ltr" translate="no">            WorkloadIdentityPool           </code></p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">resource</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">CALLBACK</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>TestIamPermissions</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc TestIamPermissions(              TestIamPermissionsRequest            </code> ) returns ( <code dir="ltr" translate="no">             TestIamPermissionsResponse            </code> )</p>
<p>Returns the caller's permissions on a <code dir="ltr" translate="no">            WorkloadIdentityPool           </code></p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UndeleteWorkloadIdentityPool</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteWorkloadIdentityPool(              UndeleteWorkloadIdentityPoolRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Undeletes a <code dir="ltr" translate="no">            WorkloadIdentityPool           </code> , as long as it was deleted fewer than 30 days ago.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.workloadIdentityPools.undelete</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UndeleteWorkloadIdentityPoolManagedIdentity</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteWorkloadIdentityPoolManagedIdentity(              UndeleteWorkloadIdentityPoolManagedIdentityRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Undeletes a <code dir="ltr" translate="no">            WorkloadIdentityPoolManagedIdentity           </code> , as long as it was deleted fewer than 30 days ago.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UndeleteWorkloadIdentityPoolNamespace</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteWorkloadIdentityPoolNamespace(              UndeleteWorkloadIdentityPoolNamespaceRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Undeletes a <code dir="ltr" translate="no">            WorkloadIdentityPoolNamespace           </code> , as long as it was deleted fewer than 30 days ago.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UndeleteWorkloadIdentityPoolProvider</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteWorkloadIdentityPoolProvider(              UndeleteWorkloadIdentityPoolProviderRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Undeletes a <code dir="ltr" translate="no">            WorkloadIdentityPoolProvider           </code> , as long as it was deleted fewer than 30 days ago.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.workloadIdentityPoolProviders.undelete</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UndeleteWorkloadIdentityPoolProviderKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteWorkloadIdentityPoolProviderKey(              UndeleteWorkloadIdentityPoolProviderKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Undeletes an <code dir="ltr" translate="no">            WorkloadIdentityPoolProviderKey           </code> , as long as it was deleted fewer than 30 days ago.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UpdateWorkloadIdentityPool</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateWorkloadIdentityPool(              UpdateWorkloadIdentityPoolRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Updates an existing <code dir="ltr" translate="no">            WorkloadIdentityPool           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.workloadIdentityPools.update</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UpdateWorkloadIdentityPoolManagedIdentity</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateWorkloadIdentityPoolManagedIdentity(              UpdateWorkloadIdentityPoolManagedIdentityRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Updates an existing <code dir="ltr" translate="no">            WorkloadIdentityPoolManagedIdentity           </code> in a <code dir="ltr" translate="no">            WorkloadIdentityPoolNamespace           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UpdateWorkloadIdentityPoolNamespace</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateWorkloadIdentityPoolNamespace(              UpdateWorkloadIdentityPoolNamespaceRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Updates an existing <code dir="ltr" translate="no">            WorkloadIdentityPoolNamespace           </code> in a <code dir="ltr" translate="no">            WorkloadIdentityPool           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UpdateWorkloadIdentityPoolProvider</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateWorkloadIdentityPoolProvider(              UpdateWorkloadIdentityPoolProviderRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Updates an existing <code dir="ltr" translate="no">            WorkloadIdentityPoolProvider           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.workloadIdentityPoolProviders.update</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

## AddAttestationRuleMetadata

This type has no fields.

Metadata for long-running AddAttestationRule operation.

## AddAttestationRuleRequest

Request message for AddAttestationRule.

Fields

`resource`

`string`

Required. The resource name of the managed identity or namespace resource to add an attestation rule to.

`attestation_rule`

`  AttestationRule  `

Required. The attestation rule to be added.

## AddAttestationRuleResponse

This type has no fields.

Response message for AddAttestationRule.

## AttestationRule

Defines which workloads can receive an identity within a pool. When an AttestationRule is defined under a managed identity, matching workloads may receive that identity.

Fields

Union field `workload_descriptor` . Descriptor for the workload. `workload_descriptor` can be only one of the following:

`google_cloud_resource`

`string`

Optional. A single workload operating on Google Cloud. For example: `//compute.googleapis.com/projects/123/uid/zones/us-central1-a/instances/12345` .

## AuditConfig

Specifies the audit configuration for a service. The configuration determines which permission types are logged, and what identities, if any, are exempted from logging. An AuditConfig must have one or more AuditLogConfigs.

If there are AuditConfigs for both `allServices` and a specific service, the union of the two AuditConfigs is used for that service: the log\_types specified in each AuditConfig are enabled, and the exempted\_members in each AuditLogConfig are exempted.

Example Policy with multiple AuditConfigs:

    {
      "audit_configs": [
        {
          "service": "allServices",
          "audit_log_configs": [
            {
              "log_type": "DATA_READ",
              "exempted_members": [
                "user:jose@example.com"
              ]
            },
            {
              "log_type": "DATA_WRITE"
            },
            {
              "log_type": "ADMIN_READ"
            }
          ]
        },
        {
          "service": "sampleservice.googleapis.com",
          "audit_log_configs": [
            {
              "log_type": "DATA_READ"
            },
            {
              "log_type": "DATA_WRITE",
              "exempted_members": [
                "user:aliya@example.com"
              ]
            }
          ]
        }
      ]
    }

For sampleservice, this policy enables DATA\_READ, DATA\_WRITE and ADMIN\_READ logging. It also exempts `jose@example.com` from DATA\_READ logging, and `aliya@example.com` from DATA\_WRITE logging.

Fields

`service`

`string`

Specifies a service that will be enabled for audit logging. For example, `storage.googleapis.com` , `cloudsql.googleapis.com` . `allServices` is a special value that covers all services.

`audit_log_configs[]`

`  AuditLogConfig  `

The configuration for logging of each type of permission.

## AuditLogConfig

Provides the configuration for logging a type of permissions. Example:

    {
      "audit_log_configs": [
        {
          "log_type": "DATA_READ",
          "exempted_members": [
            "user:jose@example.com"
          ]
        },
        {
          "log_type": "DATA_WRITE"
        }
      ]
    }

This enables 'DATA\_READ' and 'DATA\_WRITE' logging, while exempting <jose@example.com> from DATA\_READ logging.

Fields

`log_type`

`  LogType  `

The log type that this config enables.

`exempted_members[]`

`string`

Specifies the identities that do not cause logging for this type of permission. Follows the same format of `  Binding.members  ` .

## LogType

The list of valid permission types for which logging can be configured. Admin writes are always logged, and are not configurable.

Enums

`LOG_TYPE_UNSPECIFIED`

Default case. Should never be this.

`ADMIN_READ`

Admin reads. Example: CloudIAM getIamPolicy

`DATA_WRITE`

Data writes. Example: CloudSQL Users create

`DATA_READ`

Data reads. Example: CloudSQL Users list

## Binding

Associates `members` , or principals, with a `role` .

Fields

`role`

`string`

Role that is assigned to the list of `members` , or principals. For example, `roles/viewer` , `roles/editor` , or `roles/owner` .

For an overview of the IAM roles and permissions, see the [IAM documentation](https://cloud.google.com/iam/docs/roles-overview) . For a list of the available pre-defined roles, see [here](https://cloud.google.com/iam/docs/understanding-roles) .

`members[]`

`string`

Specifies the principals requesting access for a Google Cloud resource. `members` can have the following values:

  - `allUsers` : A special identifier that represents anyone who is on the internet; with or without a Google account.

  - `allAuthenticatedUsers` : A special identifier that represents anyone who is authenticated with a Google account or a service account. Does not include identities that come from external identity providers (IdPs) through identity federation.

  - `user:{emailid}` : An email address that represents a specific Google account. For example, `alice@example.com` .

<!-- end list -->

  - `serviceAccount:{emailid}` : An email address that represents a Google service account. For example, `my-other-app@appspot.gserviceaccount.com` .

  - `serviceAccount:{projectid}.svc.id.goog[{namespace}/{kubernetes-sa}]` : An identifier for a [Kubernetes service account](https://cloud.google.com/kubernetes-engine/docs/how-to/kubernetes-service-accounts) . For example, `my-project.svc.id.goog[my-namespace/my-kubernetes-sa]` .

  - `group:{emailid}` : An email address that represents a Google group. For example, `admins@example.com` .

<!-- end list -->

  - `domain:{domain}` : The G Suite domain (primary) that represents all the users of that domain. For example, `google.com` or `example.com` .

<!-- end list -->

  - `principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}` : A single identity in a workforce identity pool.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/group/{group_id}` : All workforce identities in a group.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/attribute.{attribute_name}/{attribute_value}` : All workforce identities with a specific attribute value.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/*` : All identities in a workforce identity pool.

  - `principal://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/subject/{subject_attribute_value}` : A single identity in a workload identity pool.

  - `principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/group/{group_id}` : A workload identity pool group.

  - `principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/attribute.{attribute_name}/{attribute_value}` : All identities in a workload identity pool with a certain attribute.

  - `principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/*` : All identities in a workload identity pool.

  - `deleted:user:{emailid}?uid={uniqueid}` : An email address (plus unique identifier) representing a user that has been recently deleted. For example, `alice@example.com?uid=123456789012345678901` . If the user is recovered, this value reverts to `user:{emailid}` and the recovered user retains the role in the binding.

  - `deleted:serviceAccount:{emailid}?uid={uniqueid}` : An email address (plus unique identifier) representing a service account that has been recently deleted. For example, `my-other-app@appspot.gserviceaccount.com?uid=123456789012345678901` . If the service account is undeleted, this value reverts to `serviceAccount:{emailid}` and the undeleted service account retains the role in the binding.

  - `deleted:group:{emailid}?uid={uniqueid}` : An email address (plus unique identifier) representing a Google group that has been recently deleted. For example, `admins@example.com?uid=123456789012345678901` . If the group is recovered, this value reverts to `group:{emailid}` and the recovered group retains the role in the binding.

  - `deleted:principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}` : Deleted single identity in a workforce identity pool. For example, `deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value` .

`condition`

`  Expr  `

The condition that is associated with this binding.

If the condition evaluates to `true` , then this binding applies to the current request.

If the condition evaluates to `false` , then this binding does not apply to the current request. However, a different role binding might grant the same role to one or more of the principals in this binding.

To learn which resources support conditions in their IAM policies, see the [IAM documentation](https://cloud.google.com/iam/help/conditions/resource-policies) .

## BindingDelta

One delta entry for Binding. Each individual change (only one member in each entry) to a binding will be a separate entry.

Fields

`action`

`  Action  `

The action that was performed on a Binding. Required

`role`

`string`

Role that is assigned to `members` . For example, `roles/viewer` , `roles/editor` , or `roles/owner` . Required

`member`

`string`

A single identity requesting access for a Google Cloud resource. Follows the same format of Binding.members. Required

`condition`

`  Expr  `

The condition that is associated with this binding.

## Action

The type of action performed on a Binding in a policy.

Enums

`ACTION_UNSPECIFIED`

Unspecified.

`ADD`

Addition of a Binding.

`REMOVE`

Removal of a Binding.

## CreateWorkloadIdentityPoolManagedIdentityRequest

Request message for CreateWorkloadIdentityPoolManagedIdentity.

Fields

`parent`

`string`

Required. The parent resource to create the manage identity in. The only supported location is `global` .

`workload_identity_pool_managed_identity`

`  WorkloadIdentityPoolManagedIdentity  `

Required. The managed identity to create.

`workload_identity_pool_managed_identity_id`

`string`

Required. The ID to use for the managed identity. This value must: \* contain at most 63 characters \* contain only lowercase alphanumeric characters or `-` \* start with an alphanumeric character \* end with an alphanumeric character

The prefix "gcp-" will be reserved for future uses.

## CreateWorkloadIdentityPoolNamespaceRequest

Request message for CreateWorkloadIdentityPoolNamespace.

Fields

`parent`

`string`

Required. The parent resource to create the namespace in. The only supported location is `global` .

`workload_identity_pool_namespace`

`  WorkloadIdentityPoolNamespace  `

Required. The namespace to create.

`workload_identity_pool_namespace_id`

`string`

Required. The ID to use for the namespace. This value must: \* contain at most 63 characters \* contain only lowercase alphanumeric characters or `-` \* start with an alphanumeric character \* end with an alphanumeric character

The prefix "gcp-" will be reserved for future uses.

## CreateWorkloadIdentityPoolProviderKeyRequest

Request message for CreateWorkloadIdentityPoolProviderKey.

Fields

`parent`

`string`

Required. The parent provider resource to create the key in.

`workload_identity_pool_provider_key`

`  WorkloadIdentityPoolProviderKey  `

Required. The WorkloadIdentityPoolProviderKey to create.

`workload_identity_pool_provider_key_id`

`string`

Required. The ID to use for the key, which becomes the final component of the resource name. This value should be 4-32 characters, and may contain the characters \[a-z0-9-\].

## CreateWorkloadIdentityPoolProviderRequest

Request message for CreateWorkloadIdentityPoolProvider.

Fields

`parent`

`string`

Required. The pool to create this provider in.

`workload_identity_pool_provider`

`  WorkloadIdentityPoolProvider  `

Required. The provider to create.

`workload_identity_pool_provider_id`

`string`

Required. The ID for the provider, which becomes the final component of the resource name. This value must be 4-32 characters, and may contain the characters \[a-z0-9-\]. The prefix `gcp-` is reserved for use by Google, and may not be specified.

## CreateWorkloadIdentityPoolRequest

Request message for CreateWorkloadIdentityPool.

Fields

`parent`

`string`

Required. The parent resource to create the pool in. The only supported location is `global` .

`workload_identity_pool`

`  WorkloadIdentityPool  `

Required. The pool to create.

`workload_identity_pool_id`

`string`

Required. The ID to use for the pool, which becomes the final component of the resource name. This value should be 4-32 characters, and may contain the characters \[a-z0-9-\]. The prefix `gcp-` is reserved for use by Google, and may not be specified.

## DeleteWorkloadIdentityPoolManagedIdentityRequest

Request message for DeleteWorkloadIdentityPoolManagedIdentity.

Fields

`name`

`string`

Required. The name of the managed identity to delete.

## DeleteWorkloadIdentityPoolNamespaceRequest

Request message for DeleteWorkloadIdentityPoolNamespace.

Fields

`name`

`string`

Required. The name of the namespace to delete.

## DeleteWorkloadIdentityPoolProviderKeyRequest

Request message for DeleteWorkloadIdentityPoolProviderKey.

Fields

`name`

`string`

Required. The name of the encryption key to delete.

## DeleteWorkloadIdentityPoolProviderRequest

Request message for DeleteWorkloadIdentityPoolProvider.

Fields

`name`

`string`

Required. The name of the provider to delete.

## DeleteWorkloadIdentityPoolRequest

Request message for DeleteWorkloadIdentityPool.

Fields

`name`

`string`

Required. The name of the pool to delete.

## GetIamPolicyRequest

Request message for `GetIamPolicy` method.

Fields

`resource`

`string`

REQUIRED: The resource for which the policy is being requested. See [Resource names](https://cloud.google.com/apis/design/resource_names) for the appropriate value for this field.

`options`

`  GetPolicyOptions  `

OPTIONAL: A `GetPolicyOptions` object for specifying options to `GetIamPolicy` .

## GetPolicyOptions

Encapsulates settings provided to GetIamPolicy.

Fields

`requested_policy_version`

`int32`

Optional. The maximum policy version that will be used to format the policy.

Valid values are 0, 1, and 3. Requests specifying an invalid value will be rejected.

Requests for policies with any conditional role bindings must specify version 3. Policies with no conditional role bindings may specify any valid value or leave the field unset.

The policy in the response might use the policy version that you specified, or it might use a lower policy version. For example, if you specify version 3, but the policy has no conditional role bindings, the response uses version 1.

To learn which resources support conditions in their IAM policies, see the [IAM documentation](https://cloud.google.com/iam/help/conditions/resource-policies) .

## GetWorkloadIdentityPoolManagedIdentityRequest

Request message for GetWorkloadIdentityPoolManagedIdentity.

Fields

`name`

`string`

Required. The name of the managed identity to retrieve.

## GetWorkloadIdentityPoolNamespaceRequest

Request message for GetWorkloadIdentityPoolNamespace.

Fields

`name`

`string`

Required. The name of the namespace to retrieve.

## GetWorkloadIdentityPoolProviderKeyRequest

Request message for GetWorkloadIdentityPoolProviderKey.

Fields

`name`

`string`

Required. The name of the key to retrieve.

## GetWorkloadIdentityPoolProviderRequest

Request message for GetWorkloadIdentityPoolProvider.

Fields

`name`

`string`

Required. The name of the provider to retrieve.

## GetWorkloadIdentityPoolRequest

Request message for GetWorkloadIdentityPool.

Fields

`name`

`string`

Required. The name of the pool to retrieve.

## ListAttestationRulesRequest

Request message for ListAttestationRules.

Fields

`resource`

`string`

Required. The resource name of the managed identity or namespace resource to list attestation rules of.

`filter`

`string`

Optional. A query filter. Supports the following function:

  - `container_ids()` : Returns only the AttestationRules under the specific container ids. The function expects a comma-delimited list with only project numbers and must use the format `projects/<project-number>` . For example: `container_ids(projects/<project-number-1>, projects/<project-number-2>,...)` .

`page_size`

`int32`

Optional. The maximum number of AttestationRules to return. If unspecified, at most 50 AttestationRules are returned. The maximum value is 100; values above 100 are truncated to 100.

`page_token`

`string`

Optional. A page token, received from a previous `ListWorkloadIdentityPoolProviderKeys` call. Provide this to retrieve the subsequent page.

## ListAttestationRulesResponse

Response message for ListAttestationRules.

Fields

`attestation_rules[]`

`  AttestationRule  `

A list of AttestationRules.

`next_page_token`

`string`

Optional. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## ListWorkloadIdentityPoolManagedIdentitiesRequest

Request message for ListWorkloadIdentityPoolManagedIdentities.

Fields

`parent`

`string`

Required. The parent resource to list managed identities for.

`page_size`

`int32`

The maximum number of managed identities to return. If unspecified, at most 50 managed identities are returned. The maximum value is 1000; values above are 1000 truncated to 1000.

`page_token`

`string`

A page token, received from a previous `ListWorkloadIdentityPoolManagedIdentities` call. Provide this to retrieve the subsequent page.

`show_deleted`

`bool`

Whether to return soft-deleted managed identities.

## ListWorkloadIdentityPoolManagedIdentitiesResponse

Response message for ListWorkloadIdentityPoolManagedIdentities.

Fields

`workload_identity_pool_managed_identities[]`

`  WorkloadIdentityPoolManagedIdentity  `

A list of managed identities.

`next_page_token`

`string`

A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## ListWorkloadIdentityPoolNamespacesRequest

Request message for ListWorkloadIdentityPoolNamespaces.

Fields

`parent`

`string`

Required. The parent resource to list namespaces for.

`page_size`

`int32`

The maximum number of namespaces to return. If unspecified, at most 50 namespaces are returned. The maximum value is 1000; values above are 1000 truncated to 1000.

`page_token`

`string`

A page token, received from a previous `ListWorkloadIdentityPoolNamespaces` call. Provide this to retrieve the subsequent page.

`show_deleted`

`bool`

Whether to return soft-deleted namespaces.

## ListWorkloadIdentityPoolNamespacesResponse

Response message for ListWorkloadIdentityPoolNamespaces.

Fields

`workload_identity_pool_namespaces[]`

`  WorkloadIdentityPoolNamespace  `

A list of namespaces.

`next_page_token`

`string`

A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## ListWorkloadIdentityPoolProviderKeysRequest

Request message for ListWorkloadIdentityPoolProviderKeys.

Fields

`parent`

`string`

Required. The parent provider resource to list encryption keys for.

`page_size`

`int32`

The maximum number of keys to return. If unspecified, all keys are returned. The maximum value is 10; values above 10 are truncated to 10.

`page_token`

`string`

A page token, received from a previous `ListWorkloadIdentityPoolProviderKeys` call. Provide this to retrieve the subsequent page.

`show_deleted`

`bool`

Whether to return soft deleted resources as well.

## ListWorkloadIdentityPoolProviderKeysResponse

Response message for ListWorkloadIdentityPoolProviderKeys.

Fields

`workload_identity_pool_provider_keys[]`

`  WorkloadIdentityPoolProviderKey  `

A list of WorkloadIdentityPoolProviderKey

`next_page_token`

`string`

A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## ListWorkloadIdentityPoolProvidersRequest

Request message for ListWorkloadIdentityPoolProviders.

Fields

`parent`

`string`

Required. The pool to list providers for.

`page_size`

`int32`

The maximum number of providers to return. If unspecified, at most 50 providers are returned. The maximum value is 100; values above 100 are truncated to 100.

`page_token`

`string`

A page token, received from a previous `ListWorkloadIdentityPoolProviders` call. Provide this to retrieve the subsequent page.

`show_deleted`

`bool`

Whether to return soft-deleted providers.

## ListWorkloadIdentityPoolProvidersResponse

Response message for ListWorkloadIdentityPoolProviders.

Fields

`workload_identity_pool_providers[]`

`  WorkloadIdentityPoolProvider  `

A list of providers.

`next_page_token`

`string`

A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## ListWorkloadIdentityPoolsRequest

Request message for ListWorkloadIdentityPools.

Fields

`parent`

`string`

Required. The parent resource to list pools for.

`page_size`

`int32`

The maximum number of pools to return. If unspecified, at most 50 pools are returned. The maximum value is 1000; values above are 1000 truncated to 1000.

`page_token`

`string`

A page token, received from a previous `ListWorkloadIdentityPools` call. Provide this to retrieve the subsequent page.

`show_deleted`

`bool`

Whether to return soft-deleted pools.

## ListWorkloadIdentityPoolsResponse

Response message for ListWorkloadIdentityPools.

Fields

`workload_identity_pools[]`

`  WorkloadIdentityPool  `

A list of pools.

`next_page_token`

`string`

A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## Policy

An Identity and Access Management (IAM) policy, which specifies access controls for Google Cloud resources.

A `Policy` is a collection of `bindings` . A `binding` binds one or more `members` , or principals, to a single `role` . Principals can be user accounts, service accounts, Google groups, and domains (such as G Suite). A `role` is a named list of permissions; each `role` can be an IAM predefined role or a user-created custom role.

For some types of Google Cloud resources, a `binding` can also specify a `condition` , which is a logical expression that allows access to a resource only if the expression evaluates to `true` . A condition can add constraints based on attributes of the request, the resource, or both. To learn which resources support conditions in their IAM policies, see the [IAM documentation](https://cloud.google.com/iam/help/conditions/resource-policies) .

**JSON example:**

``` 
    {
      "bindings": [
        {
          "role": "roles/resourcemanager.organizationAdmin",
          "members": [
            "user:mike@example.com",
            "group:admins@example.com",
            "domain:google.com",
            "serviceAccount:my-project-id@appspot.gserviceaccount.com"
          ]
        },
        {
          "role": "roles/resourcemanager.organizationViewer",
          "members": [
            "user:eve@example.com"
          ],
          "condition": {
            "title": "expirable access",
            "description": "Does not grant access after Sep 2020",
            "expression": "request.time < timestamp('2020-10-01T00:00:00.000Z')",
          }
        }
      ],
      "etag": "BwWWja0YfJA=",
      "version": 3
    }
```

**YAML example:**

``` 
    bindings:
    - members:
      - user:mike@example.com
      - group:admins@example.com
      - domain:google.com
      - serviceAccount:my-project-id@appspot.gserviceaccount.com
      role: roles/resourcemanager.organizationAdmin
    - members:
      - user:eve@example.com
      role: roles/resourcemanager.organizationViewer
      condition:
        title: expirable access
        description: Does not grant access after Sep 2020
        expression: request.time < timestamp('2020-10-01T00:00:00.000Z')
    etag: BwWWja0YfJA=
    version: 3
```

For a description of IAM and its features, see the [IAM documentation](https://cloud.google.com/iam/docs/) .

Fields

`version`

`int32`

Specifies the format of the policy.

Valid values are `0` , `1` , and `3` . Requests that specify an invalid value are rejected.

Any operation that affects conditional role bindings must specify version `3` . This requirement applies to the following operations:

  - Getting a policy that includes a conditional role binding
  - Adding a conditional role binding to a policy
  - Changing a conditional role binding in a policy
  - Removing any role binding, with or without a condition, from a policy that includes conditions

**Important:** If you use IAM Conditions, you must include the `etag` field whenever you call `setIamPolicy` . If you omit this field, then IAM allows you to overwrite a version `3` policy with a version `1` policy, and all of the conditions in the version `3` policy are lost.

If a policy does not include any conditions, operations on that policy may specify any valid version or leave the field unset.

To learn which resources support conditions in their IAM policies, see the [IAM documentation](https://cloud.google.com/iam/help/conditions/resource-policies) .

`bindings[]`

`  Binding  `

Associates a list of `members` , or principals, with a `role` . Optionally, may specify a `condition` that determines how and when the `bindings` are applied. Each of the `bindings` must contain at least one principal.

The `bindings` in a `Policy` can refer to up to 1,500 principals; up to 250 of these principals can be Google groups. Each occurrence of a principal counts towards these limits. For example, if the `bindings` grant 50 different roles to `user:alice@example.com` , and not to any other principal, then you can add another 1,450 principals to the `bindings` in the `Policy` .

`audit_configs[]`

`  AuditConfig  `

Specifies cloud audit logging configuration for this policy.

`etag`

`bytes`

`etag` is used for optimistic concurrency control as a way to help prevent simultaneous updates of a policy from overwriting each other. It is strongly suggested that systems make use of the `etag` in the read-modify-write cycle to perform policy updates in order to avoid race conditions: An `etag` is returned in the response to `getIamPolicy` , and systems are expected to put that etag in the request to `setIamPolicy` to ensure that their change will be applied to the same version of the policy.

**Important:** If you use IAM Conditions, you must include the `etag` field whenever you call `setIamPolicy` . If you omit this field, then IAM allows you to overwrite a version `3` policy with a version `1` policy, and all of the conditions in the version `3` policy are lost.

## PolicyDelta

The difference delta between two policies.

Fields

`binding_deltas[]`

`  BindingDelta  `

The delta for Bindings between two policies.

## RemoveAttestationRuleMetadata

This type has no fields.

Metadata for long-running RemoveAttestationRule operation.

## RemoveAttestationRuleRequest

Request message for RemoveAttestationRule.

Fields

`resource`

`string`

Required. The resource name of the managed identity or namespace resource to remove an attestation rule from.

`attestation_rule`

`  AttestationRule  `

Required. The attestation rule to be removed.

## RemoveAttestationRuleResponse

This type has no fields.

Response message for RemoveAttestationRule.

## SetAttestationRulesMetadata

This type has no fields.

Metadata for long-running SetAttestationRules operation.

## SetAttestationRulesRequest

Request message for SetAttestationRules.

Fields

`resource`

`string`

Required. The resource name of the managed identity or namespace resource to add an attestation rule to.

`attestation_rules[]`

`  AttestationRule  `

Required. The attestation rules to be set. At most 50 attestation rules can be set.

## SetAttestationRulesResponse

This type has no fields.

Response message for SetAttestationRules.

## SetIamPolicyRequest

Request message for `SetIamPolicy` method.

Fields

`resource`

`string`

REQUIRED: The resource for which the policy is being specified. See [Resource names](https://cloud.google.com/apis/design/resource_names) for the appropriate value for this field.

`policy`

`  Policy  `

REQUIRED: The complete policy to be applied to the `resource` . The size of the policy is limited to a few 10s of KB. An empty policy is a valid policy but certain Google Cloud services (such as Projects) might reject them.

`update_mask`

`  FieldMask  `

OPTIONAL: A FieldMask specifying which fields of the policy to modify. Only the fields in the mask will be modified. If no mask is provided, the following default mask is used:

`paths: "bindings, etag"`

## TestIamPermissionsRequest

Request message for `TestIamPermissions` method.

Fields

`resource`

`string`

REQUIRED: The resource for which the policy detail is being requested. See [Resource names](https://cloud.google.com/apis/design/resource_names) for the appropriate value for this field.

`permissions[]`

`string`

The set of permissions to check for the `resource` . Permissions with wildcards (such as `*` or `storage.*` ) are not allowed. For more information see [IAM Overview](https://cloud.google.com/iam/docs/overview#permissions) .

## TestIamPermissionsResponse

Response message for `TestIamPermissions` method.

Fields

`permissions[]`

`string`

A subset of `TestPermissionsRequest.permissions` that the caller is allowed.

## TrustStore

Trust store that contains trust anchors and optional intermediate CAs used in PKI to build a trust chain(trust hierarchy) and verify a client's identity.

Fields

`trust_anchors[]`

`  TrustAnchor  `

Required. List of trust anchors to be used while performing validation against a given TrustStore. The incoming end entity's certificate must be in the trust chain of one of the trust anchors here.

`intermediate_cas[]`

`  IntermediateCA  `

Optional. Set of intermediate CA certificates used for building the trust chain to the trust anchor. Important: Intermediate CAs are only supported for X.509 federation.

## IntermediateCA

Intermediate CA certificates used for building the trust chain to trust anchor

Fields

Union field `kind` .

`kind` can be only one of the following:

`pem_certificate`

`string`

PEM certificate of the PKI used for validation. Must only contain one ca certificate.

## TrustAnchor

Represents a root of trust.

Fields

Union field `kind` .

`kind` can be only one of the following:

`pem_certificate`

`string`

PEM certificate of the PKI used for validation. Must only contain one ca certificate (either root or intermediate cert).

## UndeleteWorkloadIdentityPoolManagedIdentityRequest

Request message for UndeleteWorkloadIdentityPoolManagedIdentity.

Fields

`name`

`string`

Required. The name of the managed identity to undelete.

## UndeleteWorkloadIdentityPoolNamespaceRequest

Request message for UndeleteWorkloadIdentityPoolNamespace.

Fields

`name`

`string`

Required. The name of the namespace to undelete.

## UndeleteWorkloadIdentityPoolProviderKeyRequest

Request message for UndeleteWorkloadIdentityPoolProviderKey.

Fields

`name`

`string`

Required. The name of the encryption key to undelete.

## UndeleteWorkloadIdentityPoolProviderRequest

Request message for UndeleteWorkloadIdentityPoolProvider.

Fields

`name`

`string`

Required. The name of the provider to undelete.

## UndeleteWorkloadIdentityPoolRequest

Request message for UndeleteWorkloadIdentityPool.

Fields

`name`

`string`

Required. The name of the pool to undelete.

## UpdateWorkloadIdentityPoolManagedIdentityRequest

Request message for UpdateWorkloadIdentityPoolManagedIdentity.

Fields

`workload_identity_pool_managed_identity`

`  WorkloadIdentityPoolManagedIdentity  `

Required. The managed identity to update. The `name` field is used to identify the namespace to update.

`update_mask`

`  FieldMask  `

Required. The list of fields to update.

## UpdateWorkloadIdentityPoolNamespaceRequest

Request message for UpdateWorkloadIdentityPoolNamespace.

Fields

`workload_identity_pool_namespace`

`  WorkloadIdentityPoolNamespace  `

Required. The namespace to update. The `name` field is used to identify the pool to update.

`update_mask`

`  FieldMask  `

Required. The list of fields to update.

## UpdateWorkloadIdentityPoolProviderRequest

Request message for UpdateWorkloadIdentityPoolProvider.

Fields

`workload_identity_pool_provider`

`  WorkloadIdentityPoolProvider  `

Required. The provider to update.

`update_mask`

`  FieldMask  `

Required. The list of fields to update.

## UpdateWorkloadIdentityPoolRequest

Request message for UpdateWorkloadIdentityPool.

Fields

`workload_identity_pool`

`  WorkloadIdentityPool  `

Required. The pool to update. The `name` field is used to identify the pool to update.

`update_mask`

`  FieldMask  `

Required. The list of fields to update.

## WorkloadIdentityPool

Represents a collection of workload identities. You can define IAM policies to grant these identities access to Google Cloud resources.

Fields

`name`

`string`

Output only. The resource name of the pool.

`display_name`

`string`

Optional. A display name for the pool. Cannot exceed 32 characters.

`description`

`string`

Optional. A description of the pool. Cannot exceed 256 characters.

`state`

`  State  `

Output only. The state of the pool.

`disabled`

`bool`

Optional. Whether the pool is disabled. You cannot use a disabled pool to exchange tokens, or use existing tokens to access resources. If the pool is re-enabled, existing tokens grant access again.

`mode`

`  Mode  `

Immutable. The mode the pool is operating in.

`expire_time`

`  Timestamp  `

Output only. Time after which the workload identity pool will be permanently purged and cannot be recovered.

Union field `cert_issuance_config` . Certificate issuance configuration to use for generating X.509 certificates for the workloads. `cert_issuance_config` can be only one of the following:

`inline_certificate_issuance_config`

`  InlineCertificateIssuanceConfig  `

Optional. Defines the Certificate Authority (CA) pool resources and configurations required for issuance and rotation of mTLS workload certificates.

Union field `trust_config` . Trust configuration for establishing trust with other trust domains. `trust_config` can be only one of the following:

`inline_trust_config`

`  InlineTrustConfig  `

Optional. Represents config to add additional trusted trust domains.

## InlineCertificateIssuanceConfig

Represents configuration for generating mutual TLS (mTLS) certificates for the identities within this pool.

Fields

`ca_pools`

`map<string, string>`

Optional. A required mapping of a Google Cloud region to the CA pool resource located in that region. The CA pool is used for certificate issuance, adhering to the following constraints:

  - Key format: A supported cloud region name equivalent to the location identifier in the corresponding map entry's value.

  - Value format: A valid CA pool resource path format like: "projects/{project}/locations/{location}/caPools/{ca\_pool}"

  - Region Matching: Workloads are ONLY issued certificates from CA pools within the same region. Also the CA pool region (in value) must match the workload's region (key).

`lifetime`

`  Duration  `

Optional. Lifetime of the workload certificates issued by the CA pool. Must be between 24 hours and 30 days. If not specified, this will be defaulted to 24 hours.

`key_algorithm`

`  KeyAlgorithm  `

Optional. Key algorithm to use when generating the key pair. This key pair will be used to create the certificate. If not specified, this will default to ECDSA\_P256.

`rotation_window_percentage`

`int32`

Optional. Rotation window percentage, the percentage of remaining lifetime after which certificate rotation is initiated. Must be between 50 and 80. If no value is specified, rotation window percentage is defaulted to 50.

## KeyAlgorithm

Key generation algorithm types for X.509 certificates.

Enums

`KEY_ALGORITHM_UNSPECIFIED`

Unspecified key algorithm. Defaults to ECDSA\_P256.

`RSA_2048`

Specifies RSA with a 2048-bit modulus.

`RSA_3072`

Specifies RSA with a 3072-bit modulus.

`RSA_4096`

Specifies RSA with a 4096-bit modulus.

`ECDSA_P256`

Specifies ECDSA with curve P256.

`ECDSA_P384`

Specifies ECDSA with curve P384.

## InlineTrustConfig

Defines configuration for extending trust to additional trust domains. By establishing trust with another domain, the current domain will recognize and accept certificates issued by entities within the trusted domains. Note that a trust domain automatically trusts itself, eliminating the need for explicit configuration.

Fields

`additional_trust_bundles`

` map<string, TrustStore  ` \>

Optional. Maps specific trust domains (e.g., "example.com") to their corresponding `  TrustStore  ` , which contain the trusted root certificates for that domain. There can be a maximum of 10 trust domain entries in this map.

Note that a trust domain automatically trusts itself and don't need to be specified here. If however, this WorkloadIdentityPool's trust domain contains any trust anchors in the additional\_trust\_bundles map, those trust anchors will be *appended to* the trust bundle automatically derived from your InlineCertificateIssuanceConfig's ca\_pools.

## Mode

Represents the mode for the pool.

Enums

`MODE_UNSPECIFIED`

State unspecified. New pools should not use this mode. Pools with an unspecified mode will operate as if they are in federation-only mode.

`FEDERATION_ONLY`

Federation-only mode. Federation-only pools can only be used for federating external workload identities into Google Cloud. Unless otherwise noted, no structure or format constraints are applied to workload identities in a federation-only pool, and you cannot create any resources within the pool besides providers.

`TRUST_DOMAIN`

Trust-domain mode. Trust-domain pools can be used to assign identities to Google Cloud workloads. All identities within a trust-domain pool must consist of a single namespace and individual workload identifier. The subject identifier for all identities must conform to the following format:

`ns/<namespace>/sa/<workload_identifier>`

`  WorkloadIdentityPoolProvider  ` s cannot be created within trust-domain pools.

## State

The current state of the pool.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The pool is active, and may be used in Google Cloud policies.

`DELETED`

The pool is soft-deleted. Soft-deleted pools are permanently deleted after approximately 30 days. You can restore a soft-deleted pool using `  UndeleteWorkloadIdentityPool  ` .

You cannot reuse the ID of a soft-deleted pool until it is permanently deleted.

While a pool is deleted, you cannot use it to exchange tokens, or use existing tokens to access resources. If the pool is undeleted, existing tokens grant access again.

## WorkloadIdentityPoolManagedIdentity

Represents a managed identity for a workload identity pool namespace.

Fields

`name`

`string`

Output only. The resource name of the managed identity.

`description`

`string`

Optional. A description of the managed identity. Cannot exceed 256 characters.

`state`

`  State  `

Output only. The state of the managed identity.

`disabled`

`bool`

Optional. Whether the managed identity is disabled. If disabled, credentials may no longer be issued for the identity, however existing credentials will still be accepted until they expire.

`expire_time`

`  Timestamp  `

Output only. Time after which the managed identity will be permanently purged and cannot be recovered.

## State

The current state of the managed identity.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The managed identity is active.

`DELETED`

The managed identity is soft-deleted. Soft-deleted managed identities are permanently deleted after approximately 30 days. You can restore a soft-deleted managed identity using `  UndeleteWorkloadIdentityPoolManagedIdentity  ` .

You cannot reuse the ID of a soft-deleted managed identity until it is permanently deleted.

## WorkloadIdentityPoolManagedIdentityOperationMetadata

This type has no fields.

Metadata for long-running WorkloadIdentityPoolManagedIdentity operations.

## WorkloadIdentityPoolNamespace

Represents a namespace for a workload identity pool. Namespaces are used to segment identities within the pool.

Fields

`name`

`string`

Output only. The resource name of the namespace.

`description`

`string`

Optional. A description of the namespace. Cannot exceed 256 characters.

`state`

`  State  `

Output only. The state of the namespace.

`disabled`

`bool`

Optional. Whether the namespace is disabled. If disabled, credentials may no longer be issued for identities within this namespace, however existing credentials will still be accepted until they expire.

`expire_time`

`  Timestamp  `

Output only. Time after which the namespace will be permanently purged and cannot be recovered.

Union field `owner` . Defines the owner that is allowed to mutate this resource. If present, this resource can only be mutated by the owner. `owner` can be only one of the following:

`owner_service`

`  OwnerService  `

Output only. The Google Cloud service that owns this namespace.

## OwnerService

The Google Cloud service that owns this namespace.

Fields

`principal_subject`

`string`

Required. The service agent principal subject, e.g. "serviceAccount: [service-1234@gcp-sa-gkehub.iam.gserviceaccount.com"](mailto:service-1234@gcp-sa-gkehub.iam.gserviceaccount.com%22) .

## State

The current state of the namespace.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The namespace is active.

`DELETED`

The namespace is soft-deleted. Soft-deleted namespaces are permanently deleted after approximately 30 days. You can restore a soft-deleted namespace using `  UndeleteWorkloadIdentityPoolNamespace  ` .

You cannot reuse the ID of a soft-deleted namespace until it is permanently deleted.

## WorkloadIdentityPoolNamespaceOperationMetadata

This type has no fields.

Metadata for long-running WorkloadIdentityPoolNamespace operations.

## WorkloadIdentityPoolOperationMetadata

This type has no fields.

Metadata for long-running WorkloadIdentityPool operations.

## WorkloadIdentityPoolProvider

A configuration for an external identity provider.

Fields

`name`

`string`

Output only. The resource name of the provider.

`display_name`

`string`

Optional. A display name for the provider. Cannot exceed 32 characters.

`description`

`string`

Optional. A description for the provider. Cannot exceed 256 characters.

`state`

`  State  `

Output only. The state of the provider.

`disabled`

`bool`

Optional. Whether the provider is disabled. You cannot use a disabled provider to exchange tokens. However, existing tokens still grant access.

`attribute_mapping`

`map<string, string>`

Optional. Maps attributes from authentication credentials issued by an external identity provider to Google Cloud attributes, such as `subject` and `segment` .

Each key must be a string specifying the Google Cloud IAM attribute to map to.

The following keys are supported:

  - `google.subject` : The principal IAM is authenticating. You can reference this value in IAM bindings. This is also the subject that appears in Cloud Logging logs. Cannot exceed 127 bytes.

  - `google.groups` : Groups the external identity belongs to. You can grant groups access to resources using an IAM `principalSet` binding; access applies to all members of the group.

You can also provide custom attributes by specifying `attribute.{custom_attribute}` , where `{custom_attribute}` is the name of the custom attribute to be mapped. You can define a maximum of 50 custom attributes. The maximum length of a mapped attribute key is 100 characters, and the key may only contain the characters \[a-z0-9\_\].

You can reference these attributes in IAM policies to define fine-grained access for a workload to Google Cloud resources. For example:

  - `google.subject` : `principal://iam.googleapis.com/projects/{project}/locations/{location}/workloadIdentityPools/{pool}/subject/{value}`

  - `google.groups` : `principalSet://iam.googleapis.com/projects/{project}/locations/{location}/workloadIdentityPools/{pool}/group/{value}`

  - `attribute.{custom_attribute}` : `principalSet://iam.googleapis.com/projects/{project}/locations/{location}/workloadIdentityPools/{pool}/attribute.{custom_attribute}/{value}`

Each value must be a [Common Expression Language](https://opensource.google/projects/cel) function that maps an identity provider credential to the normalized attribute specified by the corresponding map key.

You can use the `assertion` keyword in the expression to access a JSON representation of the authentication credential issued by the provider.

The maximum length of an attribute mapping expression is 2048 characters. When evaluated, the total size of all mapped attributes must not exceed 8KB.

For AWS providers, if no attribute mapping is defined, the following default mapping applies:

    {
      "google.subject":"assertion.arn",
      "attribute.aws_role":
        "assertion.arn.contains('assumed-role')"
        " ? assertion.arn.extract('{account_arn}assumed-role/')"
        "   + 'assumed-role/'"
        "   + assertion.arn.extract('assumed-role/{role_name}/')"
        " : assertion.arn",
    }

If any custom attribute mappings are defined, they must include a mapping to the `google.subject` attribute.

For OIDC providers, you must supply a custom mapping, which must include the `google.subject` attribute. For example, the following maps the `sub` claim of the incoming credential to the `subject` attribute on a Google token:

    {"google.subject": "assertion.sub"}

`attribute_condition`

`string`

Optional. [A Common Expression Language](https://opensource.google/projects/cel) expression, in plain text, to restrict what otherwise valid authentication credentials issued by the provider should not be accepted.

The expression must output a boolean representing whether to allow the federation.

The following keywords may be referenced in the expressions:

  - `assertion` : JSON representing the authentication credential issued by the provider.
  - `google` : The Google attributes mapped from the assertion in the `attribute_mappings` .
  - `attribute` : The custom attributes mapped from the assertion in the `attribute_mappings` .

The maximum length of the attribute condition expression is 4096 characters. If unspecified, all valid authentication credential are accepted.

The following example shows how to only allow credentials with a mapped `google.groups` value of `admins` :

    "'admins' in google.groups"

`expire_time`

`  Timestamp  `

Output only. Time after which the workload identity pool provider will be permanently purged and cannot be recovered.

Union field `provider_config` . Identity provider configuration types. `provider_config` can be only one of the following:

`aws`

`  Aws  `

An Amazon Web Services identity provider.

`oidc`

`  Oidc  `

An OpenId Connect 1.0 identity provider.

`saml`

`  Saml  `

An SAML 2.0 identity provider.

`x509`

`  X509  `

An X.509-type identity provider.

## Aws

Represents an Amazon Web Services identity provider.

Fields

`account_id`

`string`

Required. The AWS account ID.

## Oidc

Represents an OpenId Connect 1.0 identity provider.

Fields

`issuer_uri`

`string`

Required. The OIDC issuer URL. Must be an HTTPS endpoint. Per OpenID Connect Discovery 1.0 spec, the OIDC issuer URL is used to locate the provider's public keys (via `jwks_uri` ) for verifying tokens like the OIDC ID token. These public key types must be 'EC' or 'RSA'.

`allowed_audiences[]`

`string`

Optional. Acceptable values for the `aud` field (audience) in the OIDC token. Token exchange requests are rejected if the token audience does not match one of the configured values. Each audience may be at most 256 characters. A maximum of 10 audiences may be configured.

If this list is empty, the OIDC token audience must be equal to the full canonical resource name of the WorkloadIdentityPoolProvider, with or without the HTTPS prefix. For example:

    //iam.googleapis.com/projects/<project-number>/locations/<location>/workloadIdentityPools/<pool-id>/providers/<provider-id>
    https://iam.googleapis.com/projects/<project-number>/locations/<location>/workloadIdentityPools/<pool-id>/providers/<provider-id>

`jwks_json`

`string`

Optional. OIDC JWKs in JSON String format. For details on the definition of a JWK, see <https://tools.ietf.org/html/rfc7517> . If not set, the `jwks_uri` from the discovery document(fetched from the .well-known path of the `issuer_uri` ) will be used. Currently, RSA and EC asymmetric keys are supported. The JWK must use following format and include only the following fields: { "keys": \[ { "kty": "RSA/EC", "alg": " ", "use": "sig", "kid": " ", "n": "", "e": "", "x": "", "y": "", "crv": "" } \] }

## Saml

Represents an SAML 2.0 identity provider.

Fields

Union field `identity_provider` .

`identity_provider` can be only one of the following:

`idp_metadata_xml`

`string`

Required. SAML identity provider (IdP) configuration metadata XML doc. The XML document must comply with the [SAML 2.0 specification](https://docs.oasis-open.org/security/saml/v2.0/saml-metadata-2.0-os.pdf) . The maximum size of an acceptable XML document is 128K characters.

The SAML metadata XML document must satisfy the following constraints:

  - Must contain an IdP Entity ID.
  - Must contain at least one non-expired signing certificate.
  - For each signing certificate, the expiration must be:
      - From no more than 7 days in the future.
      - To no more than 25 years in the future.
  - Up to three IdP signing keys are allowed.

When updating the provider's metadata XML, at least one non-expired signing key must overlap with the existing metadata. This requirement is skipped if there are no non-expired signing keys present in the existing metadata.

## State

The current state of the provider.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The provider is active, and may be used to validate authentication credentials.

`DELETED`

The provider is soft-deleted. Soft-deleted providers are permanently deleted after approximately 30 days. You can restore a soft-deleted provider using `  UndeleteWorkloadIdentityPoolProvider  ` .

You cannot reuse the ID of a soft-deleted provider until it is permanently deleted.

## X509

An X.509-type identity provider represents a CA. It is trusted to assert a client identity if the client has a certificate that chains up to this CA.

Fields

`trust_store`

`  TrustStore  `

Required. A `  TrustStore  ` . Use this trust store as a wrapper to config the trust anchor and optional intermediate cas to help build the trust chain for the incoming end entity certificate. Follow the X.509 guidelines to define those PEM encoded certs. Only one trust store is currently supported.

## WorkloadIdentityPoolProviderKey

Represents a public key configuration for your workload identity pool provider. The key can be configured in your identity provider to encrypt the SAML assertions. Google holds the corresponding private key which it uses to decrypt encrypted tokens.

Fields

`name`

`string`

Output only. The resource name of the key.

`key_data`

`  KeyData  `

Immutable. Public half of the asymmetric key.

`state`

`  State  `

Output only. The state of the key.

`use`

`  KeyUse  `

Required. The purpose of the key.

`expire_time`

`  Timestamp  `

Output only. Time after which the key will be permanently purged and cannot be recovered. Note that the key may get purged before this timestamp if the total limit of keys per provider is crossed.

## KeyUse

The uses for which a workload identity pool provider key might be generated. A key has exactly one use.

Enums

`KEY_USE_UNSPECIFIED`

The key use is not known.

`ENCRYPTION`

The public key is used for encryption purposes.

## State

The current state of the key.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The key is active.

`DELETED`

The key is soft-deleted. Soft-deleted keys are permanently deleted after approximately 30 days. You can restore a soft-deleted key using `  UndeleteWorkloadIdentityPoolProviderKey  ` . While a key is deleted, you cannot use it during the federation.

## WorkloadIdentityPoolProviderKeyOperationMetadata

This type has no fields.

Metadata for long-running WorkloadIdentityPoolProviderKey operations.

## WorkloadIdentityPoolProviderOperationMetadata

This type has no fields.

Metadata for long-running WorkloadIdentityPoolProvider operations.
