---
name: documents/docs.cloud.google.com/iam/docs/reference/rpc/google.iam.admin.v1
uri: https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.admin.v1
title: Package google.iam.admin.v1
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

  - `  IAM  ` (interface)
  - `  OauthClients  ` (interface)
  - `  WorkforcePools  ` (interface)
  - `  AuditData  ` (message)
  - `  AuditData.PermissionDelta  ` (message)
  - `  CreateOauthClientCredentialRequest  ` (message)
  - `  CreateOauthClientRequest  ` (message)
  - `  CreateRoleRequest  ` (message)
  - `  CreateServiceAccountKeyRequest  ` (message)
  - `  CreateServiceAccountRequest  ` (message)
  - `  CreateWorkforcePoolProviderKeyRequest  ` (message)
  - `  CreateWorkforcePoolProviderRequest  ` (message)
  - `  CreateWorkforcePoolProviderScimTenantRequest  ` (message)
  - `  CreateWorkforcePoolProviderScimTokenRequest  ` (message)
  - `  CreateWorkforcePoolRequest  ` (message)
  - `  DeleteOauthClientCredentialRequest  ` (message)
  - `  DeleteOauthClientRequest  ` (message)
  - `  DeleteRoleRequest  ` (message)
  - `  DeleteServiceAccountKeyRequest  ` (message)
  - `  DeleteServiceAccountRequest  ` (message)
  - `  DeleteWorkforcePoolProviderKeyRequest  ` (message)
  - `  DeleteWorkforcePoolProviderRequest  ` (message)
  - `  DeleteWorkforcePoolProviderScimTenantRequest  ` (message)
  - `  DeleteWorkforcePoolProviderScimTokenRequest  ` (message)
  - `  DeleteWorkforcePoolRequest  ` (message)
  - `  DeleteWorkforcePoolSubjectRequest  ` (message)
  - `  DisableServiceAccountKeyRequest  ` (message)
  - `  DisableServiceAccountRequest  ` (message)
  - `  EnableServiceAccountKeyRequest  ` (message)
  - `  EnableServiceAccountRequest  ` (message)
  - `  GetOauthClientCredentialRequest  ` (message)
  - `  GetOauthClientRequest  ` (message)
  - `  GetRoleRequest  ` (message)
  - `  GetServiceAccountKeyRequest  ` (message)
  - `  GetServiceAccountRequest  ` (message)
  - `  GetWorkforcePoolProviderKeyRequest  ` (message)
  - `  GetWorkforcePoolProviderRequest  ` (message)
  - `  GetWorkforcePoolProviderScimTenantRequest  ` (message)
  - `  GetWorkforcePoolProviderScimTokenRequest  ` (message)
  - `  GetWorkforcePoolRequest  ` (message)
  - `  KeyData  ` (message)
  - `  KeyData.KeyFormat  ` (enum)
  - `  KeyData.KeySpec  ` (enum)
  - `  LintPolicyRequest  ` (message)
  - `  LintPolicyResponse  ` (message)
  - `  LintResult  ` (message)
  - `  LintResult.Level  ` (enum)
  - `  LintResult.Severity  ` (enum)
  - `  ListOauthClientCredentialsRequest  ` (message)
  - `  ListOauthClientCredentialsResponse  ` (message)
  - `  ListOauthClientsRequest  ` (message)
  - `  ListOauthClientsResponse  ` (message)
  - `  ListRolesRequest  ` (message)
  - `  ListRolesResponse  ` (message)
  - `  ListServiceAccountKeysRequest  ` (message)
  - `  ListServiceAccountKeysRequest.KeyType  ` (enum)
  - `  ListServiceAccountKeysResponse  ` (message)
  - `  ListServiceAccountsRequest  ` (message)
  - `  ListServiceAccountsResponse  ` (message)
  - `  ListWorkforcePoolProviderKeysRequest  ` (message)
  - `  ListWorkforcePoolProviderKeysResponse  ` (message)
  - `  ListWorkforcePoolProviderScimTenantsRequest  ` (message)
  - `  ListWorkforcePoolProviderScimTenantsResponse  ` (message)
  - `  ListWorkforcePoolProviderScimTokensRequest  ` (message)
  - `  ListWorkforcePoolProviderScimTokensResponse  ` (message)
  - `  ListWorkforcePoolProvidersRequest  ` (message)
  - `  ListWorkforcePoolProvidersResponse  ` (message)
  - `  ListWorkforcePoolsRequest  ` (message)
  - `  ListWorkforcePoolsResponse  ` (message)
  - `  OauthClient  ` (message)
  - `  OauthClient.ClientType  ` (enum)
  - `  OauthClient.GrantType  ` (enum)
  - `  OauthClient.State  ` (enum)
  - `  OauthClientCredential  ` (message)
  - `  PatchServiceAccountRequest  ` (message)
  - `  Permission  ` (message)
  - `  Permission.CustomRolesSupportLevel  ` (enum)
  - `  Permission.PermissionLaunchStage  ` (enum)
  - `  QueryAuditableServicesRequest  ` (message)
  - `  QueryAuditableServicesResponse  ` (message)
  - `  QueryAuditableServicesResponse.AuditableService  ` (message)
  - `  QueryGrantableRolesRequest  ` (message)
  - `  QueryGrantableRolesResponse  ` (message)
  - `  QueryTestablePermissionsRequest  ` (message)
  - `  QueryTestablePermissionsResponse  ` (message)
  - `  Role  ` (message)
  - `  Role.RoleLaunchStage  ` (enum)
  - `  RoleView  ` (enum)
  - `  ServiceAccount  ` (message)
  - `  ServiceAccountKey  ` (message)
  - `  ServiceAccountKey.ExtendedStatus  ` (message)
  - `  ServiceAccountKeyAlgorithm  ` (enum)
  - `  ServiceAccountKeyDisableReason  ` (enum)
  - `  ServiceAccountKeyExtendedStatusKey  ` (enum)
  - `  ServiceAccountKeyOrigin  ` (enum)
  - `  ServiceAccountPrivateKeyType  ` (enum)
  - `  ServiceAccountPublicKeyType  ` (enum)
  - `  SignBlobRequest  ` (message)
  - `  SignBlobResponse  ` (message)
  - `  SignJwtRequest  ` (message)
  - `  SignJwtResponse  ` (message)
  - `  UndeleteOauthClientRequest  ` (message)
  - `  UndeleteRoleRequest  ` (message)
  - `  UndeleteServiceAccountRequest  ` (message)
  - `  UndeleteServiceAccountResponse  ` (message)
  - `  UndeleteWorkforcePoolProviderKeyRequest  ` (message)
  - `  UndeleteWorkforcePoolProviderRequest  ` (message)
  - `  UndeleteWorkforcePoolProviderScimTenantRequest  ` (message)
  - `  UndeleteWorkforcePoolProviderScimTokenRequest  ` (message)
  - `  UndeleteWorkforcePoolRequest  ` (message)
  - `  UndeleteWorkforcePoolSubjectRequest  ` (message)
  - `  UpdateOauthClientCredentialRequest  ` (message)
  - `  UpdateOauthClientRequest  ` (message)
  - `  UpdateRoleRequest  ` (message)
  - `  UpdateWorkforcePoolProviderRequest  ` (message)
  - `  UpdateWorkforcePoolProviderScimTenantRequest  ` (message)
  - `  UpdateWorkforcePoolProviderScimTokenRequest  ` (message)
  - `  UpdateWorkforcePoolRequest  ` (message)
  - `  UploadServiceAccountKeyRequest  ` (message)
  - `  WorkforcePool  ` (message)
  - `  WorkforcePool.AccessRestrictions  ` (message)
  - `  WorkforcePool.AccessRestrictions.ServiceConfig  ` (message)
  - `  WorkforcePool.State  ` (enum)
  - `  WorkforcePoolOperationMetadata  ` (message)
  - `  WorkforcePoolProvider  ` (message)
  - `  WorkforcePoolProvider.ExtraAttributesOAuth2Client  ` (message)
  - `  WorkforcePoolProvider.ExtraAttributesOAuth2Client.AttributesType  ` (enum)
  - `  WorkforcePoolProvider.ExtraAttributesOAuth2Client.QueryParameters  ` (message)
  - `  WorkforcePoolProvider.Oidc  ` (message)
  - `  WorkforcePoolProvider.Oidc.ClientSecret  ` (message)
  - `  WorkforcePoolProvider.Oidc.ClientSecret.Value  ` (message)
  - `  WorkforcePoolProvider.Oidc.WebSsoConfig  ` (message)
  - `  WorkforcePoolProvider.Oidc.WebSsoConfig.AssertionClaimsBehavior  ` (enum)
  - `  WorkforcePoolProvider.Oidc.WebSsoConfig.ResponseType  ` (enum)
  - `  WorkforcePoolProvider.Saml  ` (message)
  - `  WorkforcePoolProvider.ScimUsage  ` (enum)
  - `  WorkforcePoolProvider.State  ` (enum)
  - `  WorkforcePoolProviderKey  ` (message)
  - `  WorkforcePoolProviderKey.KeyUse  ` (enum)
  - `  WorkforcePoolProviderKey.State  ` (enum)
  - `  WorkforcePoolProviderKeyOperationMetadata  ` (message)
  - `  WorkforcePoolProviderOperationMetadata  ` (message)
  - `  WorkforcePoolProviderScimTenant  ` (message)
  - `  WorkforcePoolProviderScimTenant.State  ` (enum)
  - `  WorkforcePoolProviderScimToken  ` (message)
  - `  WorkforcePoolProviderScimToken.State  ` (enum)
  - `  WorkforcePoolSubject  ` (message)
  - `  WorkforcePoolSubjectOperationMetadata  ` (message)

## IAM

Creates and manages Identity and Access Management (IAM) resources.

You can use this service to work with all of the following resources:

  - **Service accounts** , which identify an application or a virtual machine (VM) instance rather than a person
  - **Service account keys** , which service accounts use to authenticate with Google APIs
  - **IAM policies for service accounts** , which specify the roles that a principal has for the service account
  - **IAM custom roles** , which help you limit the number of permissions that you grant to principals

In addition, you can use this service to complete the following tasks, among others:

  - Test whether a service account can use specific permissions
  - Check which roles you can grant for a specific resource
  - Lint, or validate, condition expressions in an IAM policy

When you read data from the IAM API, each read is eventually consistent. In other words, if you write data with the IAM API, then immediately read that data, the read operation might return an older version of the data. To deal with this behavior, your application can retry the request with truncated exponential backoff.

In contrast, writing data to the IAM API is sequentially consistent. In other words, write operations are always processed in the order in which they were received.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreateRole</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateRole(              CreateRoleRequest            </code> ) returns ( <code dir="ltr" translate="no">             Role            </code> )</p>
<p>Creates a new custom <code dir="ltr" translate="no">            Role           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>CreateServiceAccount</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateServiceAccount(              CreateServiceAccountRequest            </code> ) returns ( <code dir="ltr" translate="no">             ServiceAccount            </code> )</p>
<p>Creates a <code dir="ltr" translate="no">            ServiceAccount           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>CreateServiceAccountKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateServiceAccountKey(              CreateServiceAccountKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             ServiceAccountKey            </code> )</p>
<p>Creates a <code dir="ltr" translate="no">            ServiceAccountKey           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>DeleteRole</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteRole(              DeleteRoleRequest            </code> ) returns ( <code dir="ltr" translate="no">             Role            </code> )</p>
<p>Deletes a custom <code dir="ltr" translate="no">            Role           </code> .</p>
<p>When you delete a custom role, the following changes occur immediately:</p>
<ul>
<li>You cannot bind a principal to the custom role in an IAM <code dir="ltr" translate="no">             Policy            </code> .</li>
<li>Existing bindings to the custom role are not changed, but they have no effect.</li>
<li>By default, the response from <code dir="ltr" translate="no">             ListRoles            </code> does not include the custom role.</li>
</ul>
<p>A deleted custom role still counts toward the <a href="https://cloud.google.com/iam/help/limits">custom role limit</a> until it is permanently deleted. You have 7 days to undelete the custom role. After 7 days, the following changes occur:</p>
<ul>
<li>The custom role is permanently deleted and cannot be recovered.</li>
<li>If an IAM policy contains a binding to the custom role, the binding is permanently removed.</li>
<li>The custom role no longer counts toward your custom role limit.</li>
</ul>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>DeleteServiceAccount</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteServiceAccount(              DeleteServiceAccountRequest            </code> ) returns ( <code dir="ltr" translate="no">             Empty            </code> )</p>
<p>Deletes a <code dir="ltr" translate="no">            ServiceAccount           </code> .</p>
<p><strong>Warning:</strong> After you delete a service account, you might not be able to undelete it. If you know that you need to re-enable the service account in the future, use <code dir="ltr" translate="no">            DisableServiceAccount           </code> instead.</p>
<p>If you delete a service account, IAM permanently removes the service account 30 days later. Google Cloud cannot recover the service account after it is permanently removed, even if you file a support request.</p>
<p>To help avoid unplanned outages, we recommend that you disable the service account before you delete it. Use <code dir="ltr" translate="no">            DisableServiceAccount           </code> to disable the service account, then wait at least 24 hours and watch for unintended consequences. If there are no unintended consequences, you can delete the service account.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>DeleteServiceAccountKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteServiceAccountKey(              DeleteServiceAccountKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Empty            </code> )</p>
<p>Deletes a <code dir="ltr" translate="no">            ServiceAccountKey           </code> . Deleting a service account key does not revoke short-lived credentials that have been issued based on the service account key.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>DisableServiceAccount</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DisableServiceAccount(              DisableServiceAccountRequest            </code> ) returns ( <code dir="ltr" translate="no">             Empty            </code> )</p>
<p>Disables a <code dir="ltr" translate="no">            ServiceAccount           </code> immediately.</p>
<p>If an application uses the service account to authenticate, that application can no longer call Google APIs or access Google Cloud resources. Existing access tokens for the service account are rejected, and requests for new access tokens will fail.</p>
<p>To re-enable the service account, use <code dir="ltr" translate="no">            EnableServiceAccount           </code> . After you re-enable the service account, its existing access tokens will be accepted, and you can request new access tokens.</p>
<p>To help avoid unplanned outages, we recommend that you disable the service account before you delete it. Use this method to disable the service account, then wait at least 24 hours and watch for unintended consequences. If there are no unintended consequences, you can delete the service account with <code dir="ltr" translate="no">            DeleteServiceAccount           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>DisableServiceAccountKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DisableServiceAccountKey(              DisableServiceAccountKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Empty            </code> )</p>
<p>Disable a <code dir="ltr" translate="no">            ServiceAccountKey           </code> . A disabled service account key can be re-enabled with <code dir="ltr" translate="no">            EnableServiceAccountKey           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>EnableServiceAccount</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc EnableServiceAccount(              EnableServiceAccountRequest            </code> ) returns ( <code dir="ltr" translate="no">             Empty            </code> )</p>
<p>Enables a <code dir="ltr" translate="no">            ServiceAccount           </code> that was disabled by <code dir="ltr" translate="no">            DisableServiceAccount           </code> .</p>
<p>If the service account is already enabled, then this method has no effect.</p>
<p>If the service account was disabled by other means—for example, if Google disabled the service account because it was compromised—you cannot use this method to enable the service account.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>EnableServiceAccountKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc EnableServiceAccountKey(              EnableServiceAccountKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Empty            </code> )</p>
<p>Enable a <code dir="ltr" translate="no">            ServiceAccountKey           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<p>Gets the IAM policy that is attached to a <code dir="ltr" translate="no">            ServiceAccount           </code> . This IAM policy specifies which principals have access to the service account.</p>
<p>This method does not tell you whether the service account has been granted any roles on other resources. To check whether a service account has role grants on a resource, use the <code dir="ltr" translate="no">getIamPolicy</code> method for that resource. For example, to view the role grants for a project, call the Resource Manager API's <a href="https://cloud.google.com/resource-manager/reference/rest/v1/projects/getIamPolicy">projects.getIamPolicy</a> method.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>GetRole</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetRole(              GetRoleRequest            </code> ) returns ( <code dir="ltr" translate="no">             Role            </code> )</p>
<p>Gets the definition of a <code dir="ltr" translate="no">            Role           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>GetServiceAccount</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetServiceAccount(              GetServiceAccountRequest            </code> ) returns ( <code dir="ltr" translate="no">             ServiceAccount            </code> )</p>
<p>Gets a <code dir="ltr" translate="no">            ServiceAccount           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>GetServiceAccountKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetServiceAccountKey(              GetServiceAccountKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             ServiceAccountKey            </code> )</p>
<p>Gets a <code dir="ltr" translate="no">            ServiceAccountKey           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>LintPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc LintPolicy(              LintPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             LintPolicyResponse            </code> )</p>
<p>Lints, or validates, an IAM policy. Currently checks the <code dir="ltr" translate="no">            google.iam.v1.Binding.condition           </code> field, which contains a condition expression for a role binding.</p>
<p>Successful calls to this method always return an HTTP <code dir="ltr" translate="no">200 OK</code> status code, even if the linter detects an issue in the IAM policy.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>ListRoles</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListRoles(              ListRolesRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListRolesResponse            </code> )</p>
<p>Lists every predefined <code dir="ltr" translate="no">            Role           </code> that IAM supports, or every custom role that is defined for an organization or project.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>ListServiceAccountKeys</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListServiceAccountKeys(              ListServiceAccountKeysRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListServiceAccountKeysResponse            </code> )</p>
<p>Lists every <code dir="ltr" translate="no">            ServiceAccountKey           </code> for a service account.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>ListServiceAccounts</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListServiceAccounts(              ListServiceAccountsRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListServiceAccountsResponse            </code> )</p>
<p>Lists every <code dir="ltr" translate="no">            ServiceAccount           </code> that belongs to a specific project.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>PatchServiceAccount</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc PatchServiceAccount(              PatchServiceAccountRequest            </code> ) returns ( <code dir="ltr" translate="no">             ServiceAccount            </code> )</p>
<p>Patches a <code dir="ltr" translate="no">            ServiceAccount           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>QueryAuditableServices</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc QueryAuditableServices(              QueryAuditableServicesRequest            </code> ) returns ( <code dir="ltr" translate="no">             QueryAuditableServicesResponse            </code> )</p>
<p>Returns a list of services that allow you to opt into audit logs that are not generated by default.</p>
<p>To learn more about audit logs, see the <a href="https://cloud.google.com/logging/docs/audit">Logging documentation</a> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>QueryGrantableRoles</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc QueryGrantableRoles(              QueryGrantableRolesRequest            </code> ) returns ( <code dir="ltr" translate="no">             QueryGrantableRolesResponse            </code> )</p>
<p>Lists roles that can be granted on a Google Cloud resource. A role is grantable if the IAM policy for the resource can contain bindings to the role.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>QueryTestablePermissions</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc QueryTestablePermissions(              QueryTestablePermissionsRequest            </code> ) returns ( <code dir="ltr" translate="no">             QueryTestablePermissionsResponse            </code> )</p>
<p>Lists every permission that you can test on a resource. A permission is testable if you can check whether a principal has that permission on the resource.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>SetIamPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc SetIamPolicy(              SetIamPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Policy            </code> )</p>
<p>Sets the IAM policy that is attached to a <code dir="ltr" translate="no">            ServiceAccount           </code> .</p>
<p>Use this method to grant or revoke access to the service account. For example, you could grant a principal the ability to impersonate the service account.</p>
<p>This method does not enable the service account to access other resources. To grant roles to a service account on a resource, follow these steps:</p>
<ol>
<li>Call the resource's <code dir="ltr" translate="no">getIamPolicy</code> method to get its current IAM policy.</li>
<li>Edit the policy so that it binds the service account to an IAM role for the resource.</li>
<li>Call the resource's <code dir="ltr" translate="no">setIamPolicy</code> method to update its IAM policy.</li>
</ol>
<p>For detailed instructions, see <a href="https://cloud.google.com/iam/help/service-accounts/granting-access-to-service-accounts">Manage access to project, folders, and organizations</a> or <a href="https://cloud.google.com/iam/help/access/manage-other-resources">Manage access to other resources</a> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>SignBlob</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>This method is deprecated. Use the <a href="https://cloud.google.com/iam/help/rest-credentials/v1/projects.serviceAccounts/signBlob">signBlob</a> method in the IAM Service Account Credentials API instead. If you currently use this method, see the <a href="https://cloud.google.com/iam/help/credentials/migrate-api">migration guide</a> for instructions.</p>
</blockquote>
<p><code dir="ltr" translate="no">rpc SignBlob(              SignBlobRequest            </code> ) returns ( <code dir="ltr" translate="no">             SignBlobResponse            </code> )</p>
<p>Signs a blob using the system-managed private key for a <code dir="ltr" translate="no">            ServiceAccount           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>SignJwt</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>This method is deprecated. Use the <a href="https://cloud.google.com/iam/help/rest-credentials/v1/projects.serviceAccounts/signJwt">signJwt</a> method in the IAM Service Account Credentials API instead. If you currently use this method, see the <a href="https://cloud.google.com/iam/help/credentials/migrate-api">migration guide</a> for instructions.</p>
</blockquote>
<p><code dir="ltr" translate="no">rpc SignJwt(              SignJwtRequest            </code> ) returns ( <code dir="ltr" translate="no">             SignJwtResponse            </code> )</p>
<p>Signs a JSON Web Token (JWT) using the system-managed private key for a <code dir="ltr" translate="no">            ServiceAccount           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>TestIamPermissions</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc TestIamPermissions(              TestIamPermissionsRequest            </code> ) returns ( <code dir="ltr" translate="no">             TestIamPermissionsResponse            </code> )</p>
<p>Tests whether the caller has the specified permissions on a <code dir="ltr" translate="no">            ServiceAccount           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>UndeleteRole</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteRole(              UndeleteRoleRequest            </code> ) returns ( <code dir="ltr" translate="no">             Role            </code> )</p>
<p>Undeletes a custom <code dir="ltr" translate="no">            Role           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>UndeleteServiceAccount</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteServiceAccount(              UndeleteServiceAccountRequest            </code> ) returns ( <code dir="ltr" translate="no">             UndeleteServiceAccountResponse            </code> )</p>
<p>Restores a deleted <code dir="ltr" translate="no">            ServiceAccount           </code> .</p>
<p><strong>Important:</strong> It is not always possible to restore a deleted service account. Use this method only as a last resort.</p>
<p>After you delete a service account, IAM permanently removes the service account 30 days later. There is no way to restore a deleted service account that has been permanently removed.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>UpdateRole</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateRole(              UpdateRoleRequest            </code> ) returns ( <code dir="ltr" translate="no">             Role            </code> )</p>
<p>Updates the definition of a custom <code dir="ltr" translate="no">            Role           </code> .</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>UpdateServiceAccount</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateServiceAccount(              ServiceAccount            </code> ) returns ( <code dir="ltr" translate="no">             ServiceAccount            </code> )</p>
<p><strong>Note:</strong> We are in the process of deprecating this method. Use <code dir="ltr" translate="no">            PatchServiceAccount           </code> instead.</p>
<p>Updates a <code dir="ltr" translate="no">            ServiceAccount           </code> .</p>
<p>You can update only the <code dir="ltr" translate="no">display_name</code> field.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
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
<th>UploadServiceAccountKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UploadServiceAccountKey(              UploadServiceAccountKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             ServiceAccountKey            </code> )</p>
<p>Uploads the public key portion of a key pair that you manage, and associates the public key with a <code dir="ltr" translate="no">            ServiceAccount           </code> .</p>
<p>After you upload the public key, you can use the private key from the key pair as a service account key.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

## OauthClients

Manages `  OauthClient  ` s. An `  OauthClient  ` represents a third-party application that can access Google Cloud resources.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreateOauthClient</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateOauthClient(              CreateOauthClientRequest            </code> ) returns ( <code dir="ltr" translate="no">             OauthClient            </code> )</p>
<p>Creates a new <code dir="ltr" translate="no">            OauthClient           </code> .</p>
<p>You cannot reuse the name of a deleted <code dir="ltr" translate="no">            OauthClient           </code> until 30 days after deletion.</p>
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
<th>CreateOauthClientCredential</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateOauthClientCredential(              CreateOauthClientCredentialRequest            </code> ) returns ( <code dir="ltr" translate="no">             OauthClientCredential            </code> )</p>
<p>Creates a new <code dir="ltr" translate="no">            OauthClientCredential           </code> .</p>
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
<th>DeleteOauthClient</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteOauthClient(              DeleteOauthClientRequest            </code> ) returns ( <code dir="ltr" translate="no">             OauthClient            </code> )</p>
<p>Deletes an <code dir="ltr" translate="no">            OauthClient           </code> .</p>
<p>You cannot use a deleted <code dir="ltr" translate="no">            OauthClient           </code> . However, deletion does not revoke access tokens that have already been issued. They continue to grant access. Deletion does revoke refresh tokens that have already been issued. They cannot be used to renew an access token. If the <code dir="ltr" translate="no">            OauthClient           </code> is undeleted, and the refresh tokens are not expired, they are valid for token exchange again. You can undelete an <code dir="ltr" translate="no">            OauthClient           </code> for 30 days. After 30 days, deletion is permanent. You cannot update deleted <code dir="ltr" translate="no">            OauthClient           </code> s. However, you can view and list them.</p>
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
<th>DeleteOauthClientCredential</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteOauthClientCredential(              DeleteOauthClientCredentialRequest            </code> ) returns ( <code dir="ltr" translate="no">             Empty            </code> )</p>
<p>Deletes an <code dir="ltr" translate="no">            OauthClientCredential           </code> .</p>
<p>Before deleting an <code dir="ltr" translate="no">            OauthClientCredential           </code> , it should first be disabled.</p>
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
<th>GetOauthClient</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetOauthClient(              GetOauthClientRequest            </code> ) returns ( <code dir="ltr" translate="no">             OauthClient            </code> )</p>
<p>Gets an individual <code dir="ltr" translate="no">            OauthClient           </code> .</p>
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
<th>GetOauthClientCredential</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetOauthClientCredential(              GetOauthClientCredentialRequest            </code> ) returns ( <code dir="ltr" translate="no">             OauthClientCredential            </code> )</p>
<p>Gets an individual <code dir="ltr" translate="no">            OauthClientCredential           </code> .</p>
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
<th>ListOauthClientCredentials</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListOauthClientCredentials(              ListOauthClientCredentialsRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListOauthClientCredentialsResponse            </code> )</p>
<p>Lists all <code dir="ltr" translate="no">            OauthClientCredential           </code> s in an <code dir="ltr" translate="no">            OauthClient           </code> .</p>
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
<th>ListOauthClients</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListOauthClients(              ListOauthClientsRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListOauthClientsResponse            </code> )</p>
<p>Lists all non-deleted <code dir="ltr" translate="no">            OauthClient           </code> s in a project. If <code dir="ltr" translate="no">show_deleted</code> is set to <code dir="ltr" translate="no">true</code> , then deleted <code dir="ltr" translate="no">            OauthClient           </code> s are also listed.</p>
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
<th>UndeleteOauthClient</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteOauthClient(              UndeleteOauthClientRequest            </code> ) returns ( <code dir="ltr" translate="no">             OauthClient            </code> )</p>
<p>Undeletes an <code dir="ltr" translate="no">            OauthClient           </code> , as long as it was deleted fewer than 30 days ago.</p>
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
<th>UpdateOauthClient</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateOauthClient(              UpdateOauthClientRequest            </code> ) returns ( <code dir="ltr" translate="no">             OauthClient            </code> )</p>
<p>Updates an existing <code dir="ltr" translate="no">            OauthClient           </code> .</p>
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
<th>UpdateOauthClientCredential</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateOauthClientCredential(              UpdateOauthClientCredentialRequest            </code> ) returns ( <code dir="ltr" translate="no">             OauthClientCredential            </code> )</p>
<p>Updates an existing <code dir="ltr" translate="no">            OauthClientCredential           </code> .</p>
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

## WorkforcePools

Manages WorkforcePools.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreateWorkforcePool</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateWorkforcePool(              CreateWorkforcePoolRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Creates a new <code dir="ltr" translate="no">            WorkforcePool           </code> .</p>
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
<th>CreateWorkforcePoolProvider</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateWorkforcePoolProvider(              CreateWorkforcePoolProviderRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Creates a new <code dir="ltr" translate="no">            WorkforcePoolProvider           </code> in a <code dir="ltr" translate="no">            WorkforcePool           </code> .</p>
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
<th>CreateWorkforcePoolProviderKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateWorkforcePoolProviderKey(              CreateWorkforcePoolProviderKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Creates a new <code dir="ltr" translate="no">            WorkforcePoolProviderKey           </code> in a <code dir="ltr" translate="no">            WorkforcePoolProvider           </code> .</p>
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
<th>CreateWorkforcePoolProviderScimTenant</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateWorkforcePoolProviderScimTenant(              CreateWorkforcePoolProviderScimTenantRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePoolProviderScimTenant            </code> )</p>
<p>Gemini Enterprise only. Creates a new <code dir="ltr" translate="no">            WorkforcePoolProviderScimTenant           </code> in a <code dir="ltr" translate="no">            WorkforcePoolProvider           </code> . You cannot reuse the name of a deleted SCIM tenant until 30 days after deletion.</p>
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
<th>CreateWorkforcePoolProviderScimToken</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateWorkforcePoolProviderScimToken(              CreateWorkforcePoolProviderScimTokenRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePoolProviderScimToken            </code> )</p>
<p>Gemini Enterprise only. Creates a new <code dir="ltr" translate="no">            WorkforcePoolProviderScimToken           </code> in a <code dir="ltr" translate="no">            WorkforcePoolProviderScimTenant           </code> . You cannot reuse the name of a deleted SCIM token until 30 days after deletion.</p>
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
<th>DeleteWorkforcePool</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteWorkforcePool(              DeleteWorkforcePoolRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes a <code dir="ltr" translate="no">            WorkforcePool           </code> .</p>
<p>You cannot use a deleted WorkforcePool to exchange external credentials for Google Cloud credentials. However, deletion does not revoke credentials that have already been issued. Credentials issued for a deleted pool do not grant access to resources. If the pool is undeleted, and the credentials are not expired, they grant access again. You can undelete a pool for 30 days. After 30 days, deletion is permanent. You cannot update deleted pools. However, you can view and list them.</p>
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
<th>DeleteWorkforcePoolProvider</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteWorkforcePoolProvider(              DeleteWorkforcePoolProviderRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes a <code dir="ltr" translate="no">            WorkforcePoolProvider           </code> .</p>
<p>Deleting a provider does not revoke credentials that have already been issued; they continue to grant access. You can undelete a provider for 30 days. After 30 days, deletion is permanent. You cannot update deleted providers. However, you can view and list them.</p>
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
<th>DeleteWorkforcePoolProviderKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteWorkforcePoolProviderKey(              DeleteWorkforcePoolProviderKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes a <code dir="ltr" translate="no">            WorkforcePoolProviderKey           </code> . You can undelete a key for 30 days. After 30 days, deletion is permanent.</p>
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
<th>DeleteWorkforcePoolProviderScimTenant</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteWorkforcePoolProviderScimTenant(              DeleteWorkforcePoolProviderScimTenantRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePoolProviderScimTenant            </code> )</p>
<p>Gemini Enterprise only. Deletes a <code dir="ltr" translate="no">            WorkforcePoolProviderScimTenant           </code> .</p>
<p>You can undelete a SCIM tenant for 30 days. After 30 days, deletion is permanent. You cannot update deleted SCIM tenants. However, you can view and list them.</p>
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
<th>DeleteWorkforcePoolProviderScimToken</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteWorkforcePoolProviderScimToken(              DeleteWorkforcePoolProviderScimTokenRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePoolProviderScimToken            </code> )</p>
<p>Gemini Enterprise only. Deletes a <code dir="ltr" translate="no">            WorkforcePoolProviderScimToken           </code> . You can undelete a SCIM token for 30 days. After 30 days, the SCIM token is permanently deleted. You cannot update deleted SCIM tokens, however, you can view and list them.</p>
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
<th>DeleteWorkforcePoolSubject</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteWorkforcePoolSubject(              DeleteWorkforcePoolSubjectRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes a <code dir="ltr" translate="no">            WorkforcePoolSubject           </code> .</p>
<p>Subject must not already be in a deleted state.</p>
<p>A <code dir="ltr" translate="no">            WorkforcePoolSubject           </code> is automatically created the first time an external credential is exchanged for a Google Cloud credential using a mapped <code dir="ltr" translate="no">google.subject</code> attribute. There is no endpoint to manually create a <code dir="ltr" translate="no">            WorkforcePoolSubject           </code> .</p>
<p>For 30 days after a <code dir="ltr" translate="no">            WorkforcePoolSubject           </code> is deleted, using the same <code dir="ltr" translate="no">google.subject</code> attribute in token exchanges with Google Cloud STS fails.</p>
<p>Call <code dir="ltr" translate="no">            UndeleteWorkforcePoolSubject           </code> to undelete a <code dir="ltr" translate="no">            WorkforcePoolSubject           </code> that has been deleted, within within 30 days of deleting it.</p>
<p>After 30 days, the <code dir="ltr" translate="no">            WorkforcePoolSubject           </code> is permanently deleted. At this point, a token exchange with Google Cloud STS that uses the same mapped <code dir="ltr" translate="no">google.subject</code> attribute automatically creates a new <code dir="ltr" translate="no">            WorkforcePoolSubject           </code> that is unrelated to the previously deleted <code dir="ltr" translate="no">            WorkforcePoolSubject           </code> but has the same <code dir="ltr" translate="no">google.subject</code> value.</p>
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
<p>Gets IAM policies on a <code dir="ltr" translate="no">            WorkforcePool           </code> .</p>
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
<th>GetWorkforcePool</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetWorkforcePool(              GetWorkforcePoolRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePool            </code> )</p>
<p>Gets an individual <code dir="ltr" translate="no">            WorkforcePool           </code> .</p>
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
<th>GetWorkforcePoolProvider</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetWorkforcePoolProvider(              GetWorkforcePoolProviderRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePoolProvider            </code> )</p>
<p>Gets an individual <code dir="ltr" translate="no">            WorkforcePoolProvider           </code> .</p>
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
<th>GetWorkforcePoolProviderKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetWorkforcePoolProviderKey(              GetWorkforcePoolProviderKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePoolProviderKey            </code> )</p>
<p>Gets a <code dir="ltr" translate="no">            WorkforcePoolProviderKey           </code> .</p>
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
<th>GetWorkforcePoolProviderScimTenant</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetWorkforcePoolProviderScimTenant(              GetWorkforcePoolProviderScimTenantRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePoolProviderScimTenant            </code> )</p>
<p>Gemini Enterprise only. Gets an individual <code dir="ltr" translate="no">            WorkforcePoolProviderScimTenant           </code> .</p>
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
<th>GetWorkforcePoolProviderScimToken</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetWorkforcePoolProviderScimToken(              GetWorkforcePoolProviderScimTokenRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePoolProviderScimToken            </code> )</p>
<p>Gemini Enterprise only. Gets an individual <code dir="ltr" translate="no">            WorkforcePoolProviderScimToken           </code> .</p>
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
<th>ListWorkforcePoolProviderKeys</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListWorkforcePoolProviderKeys(              ListWorkforcePoolProviderKeysRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListWorkforcePoolProviderKeysResponse            </code> )</p>
<p>Lists all non-deleted <code dir="ltr" translate="no">            WorkforcePoolProviderKey           </code> s in a <code dir="ltr" translate="no">            WorkforcePoolProvider           </code> . If <code dir="ltr" translate="no">show_deleted</code> is set to <code dir="ltr" translate="no">true</code> , then deleted keys are also listed.</p>
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
<th>ListWorkforcePoolProviderScimTenants</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListWorkforcePoolProviderScimTenants(              ListWorkforcePoolProviderScimTenantsRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListWorkforcePoolProviderScimTenantsResponse            </code> )</p>
<p>Gemini Enterprise only. Lists all non-deleted <code dir="ltr" translate="no">            WorkforcePoolProviderScimTenant           </code> s in a <code dir="ltr" translate="no">            WorkforcePoolProvider           </code> . If <code dir="ltr" translate="no">show_deleted</code> is set to <code dir="ltr" translate="no">true</code> , then deleted SCIM tenants are also listed.</p>
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
<th>ListWorkforcePoolProviderScimTokens</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListWorkforcePoolProviderScimTokens(              ListWorkforcePoolProviderScimTokensRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListWorkforcePoolProviderScimTokensResponse            </code> )</p>
<p>Gemini Enterprise only. Lists all non-deleted [WorkforcePoolProviderScimTokens][]s in a <code dir="ltr" translate="no">            WorkforcePoolProviderScimTenant           </code> . If <code dir="ltr" translate="no">show_deleted</code> is set to <code dir="ltr" translate="no">true</code> , then deleted SCIM tokens are also listed.</p>
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
<th>ListWorkforcePoolProviders</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListWorkforcePoolProviders(              ListWorkforcePoolProvidersRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListWorkforcePoolProvidersResponse            </code> )</p>
<p>Lists all non-deleted <code dir="ltr" translate="no">            WorkforcePoolProvider           </code> s in a <code dir="ltr" translate="no">            WorkforcePool           </code> . If <code dir="ltr" translate="no">show_deleted</code> is set to <code dir="ltr" translate="no">true</code> , then deleted providers are also listed.</p>
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
<th>ListWorkforcePools</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListWorkforcePools(              ListWorkforcePoolsRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListWorkforcePoolsResponse            </code> )</p>
<p>Lists all non-deleted <code dir="ltr" translate="no">            WorkforcePool           </code> s under the specified parent. If <code dir="ltr" translate="no">show_deleted</code> is set to <code dir="ltr" translate="no">true</code> , then deleted pools are also listed.</p>
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
<th>SetIamPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc SetIamPolicy(              SetIamPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Policy            </code> )</p>
<p>Sets IAM policies on a <code dir="ltr" translate="no">            WorkforcePool           </code> .</p>
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
<th>TestIamPermissions</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc TestIamPermissions(              TestIamPermissionsRequest            </code> ) returns ( <code dir="ltr" translate="no">             TestIamPermissionsResponse            </code> )</p>
<p>Returns the caller's permissions on the <code dir="ltr" translate="no">            WorkforcePool           </code> . If the pool doesn't exist, this call returns an empty set of permissions. It doesn't return a <code dir="ltr" translate="no">NOT_FOUND</code> error.</p>
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
<th>UndeleteWorkforcePool</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteWorkforcePool(              UndeleteWorkforcePoolRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Undeletes a <code dir="ltr" translate="no">            WorkforcePool           </code> , as long as it was deleted fewer than 30 days ago.</p>
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
<th>UndeleteWorkforcePoolProvider</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteWorkforcePoolProvider(              UndeleteWorkforcePoolProviderRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Undeletes a <code dir="ltr" translate="no">            WorkforcePoolProvider           </code> , as long as it was deleted fewer than 30 days ago.</p>
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
<th>UndeleteWorkforcePoolProviderKey</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteWorkforcePoolProviderKey(              UndeleteWorkforcePoolProviderKeyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Undeletes a <code dir="ltr" translate="no">            WorkforcePoolProviderKey           </code> , as long as it was deleted fewer than 30 days ago.</p>
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
<th>UndeleteWorkforcePoolProviderScimTenant</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteWorkforcePoolProviderScimTenant(              UndeleteWorkforcePoolProviderScimTenantRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePoolProviderScimTenant            </code> )</p>
<p>Gemini Enterprise only. Undeletes a <code dir="ltr" translate="no">            WorkforcePoolProviderScimTenant           </code> , that was deleted fewer than 30 days ago.</p>
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
<th>UndeleteWorkforcePoolProviderScimToken</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteWorkforcePoolProviderScimToken(              UndeleteWorkforcePoolProviderScimTokenRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePoolProviderScimToken            </code> )</p>
<p>Gemini Enterprise only. Undeletes a <code dir="ltr" translate="no">            WorkforcePoolProviderScimToken           </code> ,that was deleted fewer than 30 days ago.</p>
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
<th>UndeleteWorkforcePoolSubject</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UndeleteWorkforcePoolSubject(              UndeleteWorkforcePoolSubjectRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Undeletes a <code dir="ltr" translate="no">            WorkforcePoolSubject           </code> , as long as it was deleted fewer than 30 days ago.</p>
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
<th>UpdateWorkforcePool</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateWorkforcePool(              UpdateWorkforcePoolRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Updates an existing <code dir="ltr" translate="no">            WorkforcePool           </code> .</p>
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
<th>UpdateWorkforcePoolProvider</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateWorkforcePoolProvider(              UpdateWorkforcePoolProviderRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Updates an existing <code dir="ltr" translate="no">            WorkforcePoolProvider           </code> .</p>
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
<th>UpdateWorkforcePoolProviderScimTenant</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateWorkforcePoolProviderScimTenant(              UpdateWorkforcePoolProviderScimTenantRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePoolProviderScimTenant            </code> )</p>
<p>Gemini Enterprise only. Updates an existing <code dir="ltr" translate="no">            WorkforcePoolProviderScimTenant           </code> .</p>
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
<th>UpdateWorkforcePoolProviderScimToken</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateWorkforcePoolProviderScimToken(              UpdateWorkforcePoolProviderScimTokenRequest            </code> ) returns ( <code dir="ltr" translate="no">             WorkforcePoolProviderScimToken            </code> )</p>
<p>Gemini Enterprise only. Updates an existing <code dir="ltr" translate="no">            WorkforcePoolProviderScimToken           </code> .</p>
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

## AuditData

Audit log information specific to Cloud IAM admin APIs. This message is serialized as an `Any` type in the `ServiceData` message of an `AuditLog` message.

Fields

`permission_delta`

`  PermissionDelta  `

The permission\_delta when when creating or updating a Role.

## PermissionDelta

A PermissionDelta message to record the added\_permissions and removed\_permissions inside a role.

Fields

`added_permissions[]`

`string`

Added permissions.

`removed_permissions[]`

`string`

Removed permissions.

## CreateOauthClientCredentialRequest

Request message for CreateOauthClientCredential.

Fields

`parent`

`string`

Required. The parent resource to create the `  OauthClientCredential  ` in.

`oauth_client_credential`

`  OauthClientCredential  `

Required. The `  OauthClientCredential  ` to create.

`oauth_client_credential_id`

`string`

Required. The ID to use for the `  OauthClientCredential  ` , which becomes the final component of the resource name. This value should be 4-32 characters, and may contain the characters \[a-z0-9-\]. The prefix `gcp-` is reserved for use by Google, and may not be specified.

## CreateOauthClientRequest

Request message for CreateOauthClient.

Fields

`parent`

`string`

Required. The parent resource to create the `  OauthClient  ` in. The only supported location is `global` .

`oauth_client`

`  OauthClient  `

Required. The `  OauthClient  ` to create.

`oauth_client_id`

`string`

Required. The ID to use for the `  OauthClient  ` , which becomes the final component of the resource name. This value should be a string of 6 to 63 lowercase letters, digits, or hyphens. It must start with a letter, and cannot have a trailing hyphen. The prefix `gcp-` is reserved for use by Google, and may not be specified.

## CreateRoleRequest

The request to create a new role.

Fields

`parent`

`string`

The `parent` parameter's value depends on the target resource for the request, namely [projects](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles) or [organizations](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles) . Each resource type's `parent` value format is described below:

  - [projects.roles.create](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create) : `projects/{PROJECT_ID}` . This method creates project-level [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) . Example request URL: `https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles`

  - [organizations.roles.create](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create) : `organizations/{ORGANIZATION_ID}` . This method creates organization-level [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) . Example request URL: `https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles`

Note: Wildcard (\*) values are invalid; you must specify a complete project ID or organization ID.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `parent` :

  - `iam.roles.create`

`role_id`

`string`

The role ID to use for this role.

A role ID may contain alphanumeric characters, underscores ( `_` ), and periods ( `.` ). It must contain a minimum of 3 characters and a maximum of 64 characters.

`role`

`  Role  `

The Role resource to create.

## CreateServiceAccountKeyRequest

The service account key create request.

Fields

`name`

`string`

Required. The resource name of the service account.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccountKeys.create`

`private_key_type`

`  ServiceAccountPrivateKeyType  `

The output format of the private key. The default value is `TYPE_GOOGLE_CREDENTIALS_FILE` , which is the Google Credentials File format.

`key_algorithm`

`  ServiceAccountKeyAlgorithm  `

Which type of key and algorithm to use for the key. The default is currently a 2K RSA key. However this may change in the future.

## CreateServiceAccountRequest

The service account create request.

Fields

`name`

`string`

Required. The resource name of the project associated with the service accounts, such as `projects/my-project-123` .

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccounts.create`

`account_id`

`string`

Required. The account id that is used to generate the service account email address and a stable unique id. It is unique within a project, must be 6-30 characters long, and match the regular expression `[a-z]([-a-z0-9]*[a-z0-9])` to comply with RFC1035.

`service_account`

`  ServiceAccount  `

The `  ServiceAccount  ` resource to create. Currently, only the following values are user assignable: `display_name` and `description` .

## CreateWorkforcePoolProviderKeyRequest

Request message for CreateWorkforcePoolProviderKey.

Fields

`parent`

`string`

Required. The provider to create this key in.

`workforce_pool_provider_key`

`  WorkforcePoolProviderKey  `

Required. The WorkforcePoolProviderKey to create.

`workforce_pool_provider_key_id`

`string`

Required. The ID to use for the key, which becomes the final component of the resource name. This value must be 4-32 characters, and may contain the characters `[a-z0-9-]` .

## CreateWorkforcePoolProviderRequest

Request message for CreateWorkforcePoolProvider.

Fields

`parent`

`string`

Required. The pool to create this provider in.

Format: `locations/{location}/workforcePools/{workforce_pool_id}`

`workforce_pool_provider`

`  WorkforcePoolProvider  `

Required. The provider to create.

`workforce_pool_provider_id`

`string`

Required. The ID for the provider, which becomes the final component of the resource name. This value must be 4-32 characters, and may contain the characters `[a-z0-9-]` . The prefix `gcp-` is reserved for use by Google, and may not be specified.

## CreateWorkforcePoolProviderScimTenantRequest

Gemini Enterprise only. Request message for CreateWorkforcePoolProviderScimTenant.

Fields

`parent`

`string`

Required. Gemini Enterprise only. The parent to create SCIM tenant. Format: 'locations/{location}/workforcePools/{workforce\_pool}/providers/{provider}'

`workforce_pool_provider_scim_tenant`

`  WorkforcePoolProviderScimTenant  `

Required. Gemini Enterprise only. The SCIM tenant to create.

`workforce_pool_provider_scim_tenant_id`

`string`

Required. Gemini Enterprise only. The ID to use for the SCIM tenant, which becomes the final component of the resource name. This value should be 4-32 characters, containing the characters `[a-z0-9-]` .

## CreateWorkforcePoolProviderScimTokenRequest

Gemini Enterprise only. Request message for CreateWorkforcePoolProviderScimToken.

Fields

`parent`

`string`

Required. Gemini Enterprise only. The parent tenant to create SCIM token. Format: 'locations/{location}/workforcePools/{workforce\_pool}/providers/{provider}/scimTenants/{scim\_tenant}'

`workforce_pool_provider_scim_token`

`  WorkforcePoolProviderScimToken  `

Required. Gemini Enterprise only. The SCIM token to create.

`workforce_pool_provider_scim_token_id`

`string`

Required. Gemini Enterprise only. The ID to use for the SCIM token, which becomes the final component of the resource name. This value should be 4-32 characters and follow the pattern: `([a-z]([a-z0-9\\-]{2,30}[a-z0-9]))`

## CreateWorkforcePoolRequest

Request message for CreateWorkforcePool.

Fields

`workforce_pool`

`  WorkforcePool  `

Required. The pool to create.

`location`

`string`

Optional. The location of the pool to create.

Format: `locations/{location}` .

`workforce_pool_id`

`string`

Optional. The ID to use for the pool, which becomes the final component of the resource name. The IDs must be a globally unique string of 6 to 63 lowercase letters, digits, or hyphens. It must start with a letter, and cannot have a trailing hyphen. The prefix `gcp-` is reserved for use by Google, and may not be specified.

## DeleteOauthClientCredentialRequest

Request message for DeleteOauthClientCredential.

Fields

`name`

`string`

Required. The name of the `  OauthClientCredential  ` to delete.

Format: `projects/{project}/locations/{location}/oauthClients/{oauth_client}/credentials/{credential}` .

## DeleteOauthClientRequest

Request message for DeleteOauthClient.

Fields

`name`

`string`

Required. The name of the `  OauthClient  ` to delete.

Format: `projects/{project}/locations/{location}/oauthClients/{oauth_client}` .

## DeleteRoleRequest

The request to delete an existing role.

Fields

`name`

`string`

The `name` parameter's value depends on the target resource for the request, namely [projects](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles) or [organizations](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles) . Each resource type's `name` value format is described below:

  - [projects.roles.delete](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete) : `projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}` . This method deletes only [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) that have been created at the project level. Example request URL: `https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}`

  - [organizations.roles.delete](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete) : `organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}` . This method deletes only [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) that have been created at the organization level. Example request URL: `https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}`

Note: Wildcard (\*) values are invalid; you must specify a complete project ID or organization ID.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.roles.delete`

`etag`

`bytes`

Used to perform a consistent read-modify-write.

## DeleteServiceAccountKeyRequest

The service account key delete request.

Fields

`name`

`string`

Required. The resource name of the service account key.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}/keys/{KEY_ID}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}/keys/{KEY_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}/keys/{KEY_ID}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}/keys/{KEY_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account key `projects/-/serviceAccounts/fake@example.com/keys/fake-key` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccountKeys.delete`

## DeleteServiceAccountRequest

The service account delete request.

Fields

`name`

`string`

Required. The resource name of the service account.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccounts.delete`

## DeleteWorkforcePoolProviderKeyRequest

Request message for DeleteWorkforcePoolProviderKey.

Fields

`name`

`string`

Required. The name of the key to delete.

## DeleteWorkforcePoolProviderRequest

Request message for DeleteWorkforcePoolProvider.

Fields

`name`

`string`

Required. The name of the provider to delete.

Format: `locations/{location}/workforcePools/{workforce_pool_id}/providers/{provider_id}`

## DeleteWorkforcePoolProviderScimTenantRequest

Gemini Enterprise only. Request message for DeleteWorkforcePoolProviderScimTenant.

Fields

`name`

`string`

Required. Gemini Enterprise only. The name of the SCIM tenant to delete.

Format: `locations/{location}/workforcePools/{workforce_pool}/providers/{provider}/scimTenants/{scim_tenant}`

`hard_delete`

`bool`

Optional. Deletes the SCIM tenant immediately. This operation cannot be undone.

## DeleteWorkforcePoolProviderScimTokenRequest

Gemini Enterprise only. Request message for DeleteWorkforcePoolProviderScimToken.

Fields

`name`

`string`

Required. Gemini Enterprise only. The name of the SCIM token to delete.

Format: `locations/{location}/workforcePools/{workforce_pool}/providers/{provider}/scimTenants/{scim_tenant}/tokens/{token}`

## DeleteWorkforcePoolRequest

Request message for DeleteWorkforcePool.

Fields

`name`

`string`

Required. The name of the pool to delete.

Format: `locations/{location}/workforcePools/{workforce_pool_id}`

## DeleteWorkforcePoolSubjectRequest

Request message for \[DeleteWorkforcePoolSubject\]\[\].

Fields

`name`

`string`

Required. The resource name of the `  WorkforcePoolSubject  ` . Special characters, like `/` and `:` , must be escaped, because all URLs need to conform to the "When to Escape and Unescape" section of [RFC3986](https://www.ietf.org/rfc/rfc2396.txt) .

Format: `locations/{location}/workforcePools/{workforce_pool_id}/subjects/{subject_id}`

## DisableServiceAccountKeyRequest

The service account key disable request.

Fields

`name`

`string`

Required. The resource name of the service account key.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}/keys/{KEY_ID}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}/keys/{KEY_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}/keys/{KEY_ID}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}/keys/{KEY_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account key `projects/-/serviceAccounts/fake@example.com/keys/fake-key` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccountKeys.disable`

`service_account_key_disable_reason`

`  ServiceAccountKeyDisableReason  `

Optional. Describes the reason this key is being disabled. If unspecified, the default value of SERVICE\_ACCOUNT\_KEY\_DISABLE\_REASON\_USER\_INITIATED will be used.

`extended_status_message`

`string`

Optional. Usable by internal google services only. An extended\_status\_message can be used to include additional information about the key, such as its private key data being exposed on a public repository like GitHub.

## DisableServiceAccountRequest

The service account disable request.

Fields

`name`

`string`

The resource name of the service account.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccounts.disable`

## EnableServiceAccountKeyRequest

The service account key enable request.

Fields

`name`

`string`

Required. The resource name of the service account key.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}/keys/{KEY_ID}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}/keys/{KEY_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}/keys/{KEY_ID}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}/keys/{KEY_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account key `projects/-/serviceAccounts/fake@example.com/keys/fake-key` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccountKeys.enable`

## EnableServiceAccountRequest

The service account enable request.

Fields

`name`

`string`

The resource name of the service account.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccounts.enable`

## GetOauthClientCredentialRequest

Request message for GetOauthClientCredential.

Fields

`name`

`string`

Required. The name of the `  OauthClientCredential  ` to retrieve.

Format: `projects/{project}/locations/{location}/oauthClients/{oauth_client}/credentials/{credential}` .

## GetOauthClientRequest

Request message for GetOauthClient.

Fields

`name`

`string`

Required. The name of the `  OauthClient  ` to retrieve.

Format: `projects/{project}/locations/{location}/oauthClients/{oauth_client}` .

## GetRoleRequest

The request to get the definition of an existing role.

Fields

`name`

`string`

The `name` parameter's value depends on the target resource for the request, namely [roles](https://cloud.google.com/iam/docs/reference/rest/v1/roles) , [projects](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles) , or [organizations](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles) . Each resource type's `name` value format is described below:

  - [roles.get](https://cloud.google.com/iam/docs/reference/rest/v1/roles/get) : `roles/{ROLE_NAME}` . This method returns results from all [predefined roles](https://cloud.google.com/iam/docs/understanding-roles#predefined_roles) in IAM. Example request URL: `https://iam.googleapis.com/v1/roles/{ROLE_NAME}`

  - [projects.roles.get](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/get) : `projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}` . This method returns only [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) that have been created at the project level. Example request URL: `https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}`

  - [organizations.roles.get](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/get) : `organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}` . This method returns only [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) that have been created at the organization level. Example request URL: `https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}`

Note: Wildcard (\*) values are invalid; you must specify a complete project ID or organization ID.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.roles.get`

## GetServiceAccountKeyRequest

The service account key get by id request.

Fields

`name`

`string`

Required. The resource name of the service account key.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}/keys/{KEY_ID}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}/keys/{KEY_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}/keys/{KEY_ID}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}/keys/{KEY_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account key `projects/-/serviceAccounts/fake@example.com/keys/fake-key` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccountKeys.get`

`public_key_type`

`  ServiceAccountPublicKeyType  `

Optional. The output format of the public key. The default is `TYPE_NONE` , which means that the public key is not returned.

## GetServiceAccountRequest

The service account get request.

Fields

`name`

`string`

Required. The resource name of the service account.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccounts.get`

## GetWorkforcePoolProviderKeyRequest

Request message for GetWorkforcePoolProviderKey.

Fields

`name`

`string`

Required. The name of the key to retrieve.

## GetWorkforcePoolProviderRequest

Request message for GetWorkforcePoolProvider.

Fields

`name`

`string`

Required. The name of the provider to retrieve.

Format: `locations/{location}/workforcePools/{workforce_pool_id}/providers/{provider_id}`

## GetWorkforcePoolProviderScimTenantRequest

Gemini Enterprise only. Request message for GetWorkforcePoolProviderScimTenant.

Fields

`name`

`string`

Required. Gemini Enterprise only. The name of the SCIM tenant to retrieve.

Format: `locations/{location}/workforcePools/{workforce_pool}/providers/{provider}/scimTenants/{scim_tenant}`

## GetWorkforcePoolProviderScimTokenRequest

Gemini Enterprise only. Request message for GetWorkforcePoolProviderScimToken.

Fields

`name`

`string`

Required. Gemini Enterprise only. The name of the SCIM token to retrieve.

Format: `locations/{location}/workforcePools/{workforce_pool}/providers/{provider}/scimTenants/{scim_tenant}/tokens/{token}`

## GetWorkforcePoolRequest

Request message for GetWorkforcePool.

Fields

`name`

`string`

Required. The name of the pool to retrieve.

Format: `locations/{location}/workforcePools/{workforce_pool_id}`

## KeyData

Represents a public key data along with its format.

Fields

`format`

`  KeyFormat  `

Output only. The format of the key.

`not_before_time`

`  Timestamp  `

Output only. Earliest timestamp when this key is valid. Attempts to use this key before this time will fail. Only present if the key data represents a X.509 certificate.

`not_after_time`

`  Timestamp  `

Output only. Latest timestamp when this key is valid. Attempts to use this key after this time will fail. Only present if the key data represents a X.509 certificate.

`key`

`string`

Output only. The key data. The format of the key is represented by the `  format  ` field.

`key_spec`

`  KeySpec  `

Required. The specifications for the key.

## KeyFormat

The supported formats for the public key.

Enums

`KEY_FORMAT_UNSPECIFIED`

No format has been specified. This is an invalid format and must not be used.

`RSA_X509_PEM`

A RSA public key wrapped in an X.509v3 certificate ( [RFC5280](https://www.ietf.org/rfc/rfc5280.txt) ), encoded in base64, and wrapped in [public certificate label](https://datatracker.ietf.org/doc/html/rfc7468#section-5.1) .

## KeySpec

Allowed list of specifications for the key.

Enums

`KEY_SPEC_UNSPECIFIED`

No key specification specified.

`RSA_2048`

A 2048 bit RSA key.

`RSA_3072`

A 3072 bit RSA key.

`RSA_4096`

A 4096 bit RSA key.

## LintPolicyRequest

The request to lint an IAM policy object.

Fields

`full_resource_name`

`string`

The full resource name of the policy this lint request is about.

The name follows the Google Cloud format for full resource names. For example, a Google Cloud project with ID `my-project` will be named `//cloudresourcemanager.googleapis.com/projects/my-project` .

The resource name is not used to read a policy from IAM. Only the data in the request object is linted.

Union field `lint_object` . Required. The IAM object to be linted. `lint_object` can be only one of the following:

`condition`

`  Expr  `

`  google.iam.v1.Binding.condition  ` object to be linted.

## LintPolicyResponse

The response of a lint operation. An empty response indicates the operation was able to fully execute and no lint issue was found.

Fields

`lint_results[]`

`  LintResult  `

List of lint results sorted by `severity` in descending order.

## LintResult

Structured response of a single validation unit.

Fields

`level`

`  Level  `

The validation unit level.

`validation_unit_name`

`string`

The validation unit name, for instance "lintValidationUnits/ConditionComplexityCheck".

`severity`

`  Severity  `

The validation unit severity.

`field_name`

`string`

The name of the field for which this lint result is about.

For nested messages `field_name` consists of names of the embedded fields separated by period character. The top-level qualifier is the input object to lint in the request. For example, the `field_name` value `condition.expression` identifies a lint result for the `expression` field of the provided condition.

`location_offset`

`int32`

0-based character position of problematic construct within the object identified by `field_name` . Currently, this is populated only for condition expression.

`debug_message`

`string`

Human readable debug message associated with the issue.

## Level

Possible Level values of a validation unit corresponding to its domain of discourse.

Enums

`LEVEL_UNSPECIFIED`

Level is unspecified.

`CONDITION`

A validation unit which operates on an individual condition within a binding.

## Severity

Possible Severity values of an issued result.

Enums

`SEVERITY_UNSPECIFIED`

Severity is unspecified.

`ERROR`

A validation unit returns an error only for critical issues. If an attempt is made to set the problematic policy without rectifying the critical issue, it causes the `setPolicy` operation to fail.

`WARNING`

Any issue which is severe enough but does not cause an error. For example, suspicious constructs in the input object will not necessarily fail `setPolicy` , but there is a high likelihood that they won't behave as expected during policy evaluation in `checkPolicy` . This includes the following common scenarios:

  - Unsatisfiable condition: Expired timestamp in date/time condition.
  - Ineffective condition: Condition on a \<principal, role\> pair which is granted unconditionally in another binding of the same policy.

`NOTICE`

Reserved for the issues that are not severe as `ERROR` / `WARNING` , but need special handling. For instance, messages about skipped validation units are issued as `NOTICE` .

`INFO`

Any informative statement which is not severe enough to raise `ERROR` / `WARNING` / `NOTICE` , like auto-correction recommendations on the input content. Note that current version of the linter does not utilize `INFO` .

`DEPRECATED`

Deprecated severity level.

## ListOauthClientCredentialsRequest

Request message for ListOauthClientCredentials.

Fields

`parent`

`string`

Required. The parent to list `  OauthClientCredential  ` s for.

## ListOauthClientCredentialsResponse

Response message for ListOauthClientCredentials.

Fields

`oauth_client_credentials[]`

`  OauthClientCredential  `

A list of `  OauthClientCredential  ` s.

## ListOauthClientsRequest

Request message for ListOauthClients.

Fields

`parent`

`string`

Required. The parent to list `  OauthClient  ` s for.

`page_size`

`int32`

Optional. The maximum number of `  OauthClient  ` s to return. If unspecified, at most 50 `  OauthClient  ` s will be returned. The maximum value is 100; values above 100 are truncated to 100.

`page_token`

`string`

Optional. A page token, received from a previous `ListOauthClients` call. Provide this to retrieve the subsequent page.

`show_deleted`

`bool`

Optional. Whether to return soft-deleted `  OauthClient  ` s.

## ListOauthClientsResponse

Response message for ListOauthClients.

Fields

`oauth_clients[]`

`  OauthClient  `

A list of `  OauthClient  ` s.

`next_page_token`

`string`

Optional. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## ListRolesRequest

The request to get all roles defined under a resource.

Fields

`parent`

`string`

The `parent` parameter's value depends on the target resource for the request, namely [roles](https://cloud.google.com/iam/docs/reference/rest/v1/roles) , [projects](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles) , or [organizations](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles) . Each resource type's `parent` value format is described below:

  - [roles.list](https://cloud.google.com/iam/docs/reference/rest/v1/roles/list) : An empty string. This method doesn't require a resource; it simply returns all [predefined roles](https://cloud.google.com/iam/docs/understanding-roles#predefined_roles) in IAM. Example request URL: `https://iam.googleapis.com/v1/roles`

  - [projects.roles.list](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/list) : `projects/{PROJECT_ID}` . This method lists all project-level [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) . Example request URL: `https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles`

  - [organizations.roles.list](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list) : `organizations/{ORGANIZATION_ID}` . This method lists all organization-level [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) . Example request URL: `https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles`

Note: Wildcard (\*) values are invalid; you must specify a complete project ID or organization ID.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `parent` :

  - `iam.roles.list`

`page_size`

`int32`

Optional limit on the number of roles to include in the response.

The default is 300, and the maximum is 1,000.

`page_token`

`string`

Optional pagination token returned in an earlier ListRolesResponse.

`view`

`  RoleView  `

Optional view for the returned Role objects. When `FULL` is specified, the `includedPermissions` field is returned, which includes a list of all permissions in the role. The default value is `BASIC` , which does not return the `includedPermissions` field.

`show_deleted`

`bool`

Include Roles that have been deleted.

## ListRolesResponse

The response containing the roles defined under a resource.

Fields

`roles[]`

`  Role  `

The Roles defined on this resource.

`next_page_token`

`string`

To retrieve the next page of results, set `ListRolesRequest.page_token` to this value.

## ListServiceAccountKeysRequest

The service account keys list request.

Fields

`name`

`string`

Required. The resource name of the service account.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccountKeys.list`

`key_types[]`

`  KeyType  `

Filters the types of keys the user wants to include in the list response. Duplicate key types are not allowed. If no key type is provided, all keys are returned.

## KeyType

`KeyType` filters to selectively retrieve certain varieties of keys.

Enums

`KEY_TYPE_UNSPECIFIED`

Unspecified key type. The presence of this in the message will immediately result in an error.

`USER_MANAGED`

User-managed keys (managed and rotated by the user).

`SYSTEM_MANAGED`

System-managed keys (managed and rotated by Google).

## ListServiceAccountKeysResponse

The service account keys list response.

Fields

`keys[]`

`  ServiceAccountKey  `

The public keys for the service account.

## ListServiceAccountsRequest

The service account list request.

Fields

`name`

`string`

Required. The resource name of the project associated with the service accounts, such as `projects/my-project-123` .

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccounts.list`

`page_size`

`int32`

Optional limit on the number of service accounts to include in the response. Further accounts can subsequently be obtained by including the `  ListServiceAccountsResponse.next_page_token  ` in a subsequent request.

The default is 20, and the maximum is 100.

`page_token`

`string`

Optional pagination token returned in an earlier `  ListServiceAccountsResponse.next_page_token  ` .

## ListServiceAccountsResponse

The service account list response.

Fields

`accounts[]`

`  ServiceAccount  `

The list of matching service accounts.

`next_page_token`

`string`

To retrieve the next page of results, set `  ListServiceAccountsRequest.page_token  ` to this value.

## ListWorkforcePoolProviderKeysRequest

Request message for ListWorkforcePoolProviderKeys.

Fields

`parent`

`string`

Required. The provider resource to list encryption keys for.

Format: `locations/{location}/workforcePools/{workforce_pool_id}/providers/{provider_id}`

`page_size`

`int32`

The maximum number of keys to return. If unspecified, all keys are returned. The maximum value is 10; values above 10 are truncated to 10.

`page_token`

`string`

A page token, received from a previous `ListWorkforcePoolProviderKeys` call. Provide this to retrieve the subsequent page.

`show_deleted`

`bool`

Whether to return soft-deleted keys.

## ListWorkforcePoolProviderKeysResponse

Response message for ListWorkforcePoolProviderKeys.

Fields

`workforce_pool_provider_keys[]`

`  WorkforcePoolProviderKey  `

A list of WorkforcePoolProviderKeys.

`next_page_token`

`string`

A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## ListWorkforcePoolProviderScimTenantsRequest

Gemini Enterprise only. Request message for ListWorkforcePoolProviderScimTenants.

Fields

`parent`

`string`

Required. Gemini Enterprise only. The parent to list SCIM tenants. Format: 'locations/{location}/workforcePools/{workforce\_pool}/providers/{provider}'

`page_size`

`int32`

Optional. Gemini Enterprise only. The maximum number of SCIM tenants to return. If unspecified, at most 50 SCIM tenants will be returned. The maximum value is 100; values above 100 are truncated to 100.

`page_token`

`string`

Optional. Gemini Enterprise only. A page token, received from a previous `ListScimTenants` call. Provide this to retrieve the subsequent page.

`show_deleted`

`bool`

Optional. Gemini Enterprise only. Whether to return soft-deleted SCIM tenants.

## ListWorkforcePoolProviderScimTenantsResponse

Gemini Enterprise only. Response message for ListWorkforcePoolProviderScimTenants.

Fields

`workforce_pool_provider_scim_tenants[]`

`  WorkforcePoolProviderScimTenant  `

Output only. Gemini Enterprise only. A list of SCIM tenants.

`next_page_token`

`string`

Optional. Gemini Enterprise only. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## ListWorkforcePoolProviderScimTokensRequest

Gemini Enterprise only. Request message for ListWorkforcePoolProviderScimTokens.

Fields

`parent`

`string`

Required. Gemini Enterprise only. The parent to list SCIM tokens. Format: 'locations/{location}/workforcePools/{workforce\_pool}/providers/{provider}/scimTenants/{scim\_tenant}'

`page_size`

`int32`

Optional. Gemini Enterprise only. The maximum number of SCIM tokens to return. If unspecified, at most 2 SCIM tokens will be returned.

`page_token`

`string`

Optional. Gemini Enterprise only. A page token, received from a previous `ListWorkforcePoolProviderScimTokens` call. Provide this to retrieve the subsequent page.

`show_deleted`

`bool`

Optional. Gemini Enterprise only. Whether to return soft-deleted SCIM tokens.

## ListWorkforcePoolProviderScimTokensResponse

Gemini Enterprise only. Response message for ListWorkforcePoolProviderScimTokens.

Fields

`workforce_pool_provider_scim_tokens[]`

`  WorkforcePoolProviderScimToken  `

Output only. Gemini Enterprise only. A list of SCIM tokens.

`next_page_token`

`string`

Optional. Gemini Enterprise only. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## ListWorkforcePoolProvidersRequest

Request message for ListWorkforcePoolProviders.

Fields

`parent`

`string`

Required. The pool to list providers for.

Format: `locations/{location}/workforcePools/{workforce_pool_id}`

`page_size`

`int32`

The maximum number of providers to return. If unspecified, at most 50 providers are returned. The maximum value is 100; values above 100 are truncated to 100.

`page_token`

`string`

A page token, received from a previous `ListWorkforcePoolProviders` call. Provide this to retrieve the subsequent page.

`show_deleted`

`bool`

Whether to return soft-deleted providers.

## ListWorkforcePoolProvidersResponse

Response message for ListWorkforcePoolProviders.

Fields

`workforce_pool_providers[]`

`  WorkforcePoolProvider  `

A list of providers.

`next_page_token`

`string`

A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## ListWorkforcePoolsRequest

Request message for ListWorkforcePools.

Fields

`parent`

`string`

Required. The parent resource to list pools for.

Format: `organizations/{org-id}` .

`page_size`

`int32`

The maximum number of pools to return. The default value is 50. The maximum value is 100.

`page_token`

`string`

A page token, received from a previous `ListWorkforcePools` call. Provide this to retrieve the subsequent page.

`show_deleted`

`bool`

Whether to return soft-deleted pools.

`location`

`string`

The location of the pool.

Format: `locations/{location}` .

## ListWorkforcePoolsResponse

Response message for ListWorkforcePools.

Fields

`workforce_pools[]`

`  WorkforcePool  `

A list of pools.

`next_page_token`

`string`

A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## OauthClient

Represents an `  OauthClient  ` . Used to access Google Cloud resources on behalf of a Workforce Identity Federation user by using OAuth 2.0 Protocol to obtain an access token from Google Cloud.

Fields

`name`

`string`

Immutable. Identifier. The resource name of the `  OauthClient  ` .

Format: `projects/{project}/locations/{location}/oauthClients/{oauth_client}` .

`state`

`  State  `

Output only. The state of the `  OauthClient  ` .

`disabled`

`bool`

Optional. Whether the `  OauthClient  ` is disabled. You cannot use a disabled OAuth client.

`client_id`

`string`

Output only. The system-generated `  OauthClient  ` id.

`display_name`

`string`

Optional. A user-specified display name of the `  OauthClient  ` .

Cannot exceed 32 characters.

`description`

`string`

Optional. A user-specified description of the `  OauthClient  ` .

Cannot exceed 256 characters.

`client_type`

`  ClientType  `

Immutable. The type of `  OauthClient  ` . Either public or private. For private clients, the client secret can be managed using the dedicated `  OauthClientCredential  ` resource.

`allowed_grant_types[]`

`  GrantType  `

Required. The list of OAuth grant types is allowed for the `  OauthClient  ` .

`allowed_scopes[]`

`string`

Required. The list of scopes that the `  OauthClient  ` is allowed to request during OAuth flows.

The following scopes are supported:

  - `https://www.googleapis.com/auth/cloud-platform` : See, edit, configure, and delete your Google Cloud data and see the email address for your Google Account.

`allowed_redirect_uris[]`

`string`

Required. The list of redirect uris that is allowed to redirect back when authorization process is completed.

`expire_time`

`  Timestamp  `

Output only. Time after which the `  OauthClient  ` will be permanently purged and cannot be recovered.

## ClientType

The type of `  OauthClient  ` .

Enums

`CLIENT_TYPE_UNSPECIFIED`

Should not be used.

`PUBLIC_CLIENT`

Public client has no secret.

`CONFIDENTIAL_CLIENT`

Private client.

## GrantType

The OAuth grant type.

Enums

`GRANT_TYPE_UNSPECIFIED`

Should not be used.

`AUTHORIZATION_CODE_GRANT`

Authorization code grant.

`REFRESH_TOKEN_GRANT`

Refresh token grant.

## State

The current state of the `  OauthClient  ` .

Enums

`STATE_UNSPECIFIED`

Default value. This value is unused.

`ACTIVE`

The `  OauthClient  ` is active.

`DELETED`

The `  OauthClient  ` is soft-deleted. Soft-deleted `  OauthClient  ` is permanently deleted after approximately 30 days unless restored via `UndeleteOauthClient` .

## OauthClientCredential

Represents an `  OauthClientCredential  ` . Used to authenticate an `  OauthClient  ` while accessing Google Cloud resources on behalf of a user by using OAuth 2.0 Protocol.

Fields

`name`

`string`

Immutable. Identifier. The resource name of the `  OauthClientCredential  ` .

Format: `projects/{project}/locations/{location}/oauthClients/{oauth_client}/credentials/{credential}`

`disabled`

`bool`

Optional. Whether the `  OauthClientCredential  ` is disabled. You cannot use a disabled `  OauthClientCredential  ` .

`display_name`

`string`

Optional. A user-specified display name of the `  OauthClientCredential  ` .

Cannot exceed 32 characters.

Union field `credential` .

`credential` can be only one of the following:

`client_secret`

`string`

Output only. The system-generated OAuth client secret.

The client secret must be stored securely. If the client secret is leaked, you must delete and re-create the client credential. To learn more, see [OAuth client and credential security risks and mitigations](https://cloud.google.com/iam/docs/workforce-oauth-app#security)

## PatchServiceAccountRequest

The service account patch request.

You can patch only the `display_name` and `description` fields. You must use the `update_mask` field to specify which of these fields you want to patch.

Only the fields specified in the request are guaranteed to be returned in the response. Other fields may be empty in the response.

Fields

`service_account`

`  ServiceAccount  `

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `serviceAccount` :

  - `iam.serviceAccounts.update`

`update_mask`

`  FieldMask  `

## Permission

A permission which can be included by a role.

Fields

`name`

`string`

The name of this Permission.

`title`

`string`

The title of this Permission.

`description`

`string`

A brief description of what this Permission is used for.

` only_in_predefined_roles (deprecated)  `

`bool`

> This item is deprecated\!

`stage`

`  PermissionLaunchStage  `

The current launch stage of the permission.

`custom_roles_support_level`

`  CustomRolesSupportLevel  `

The current custom role support level.

`api_disabled`

`bool`

The service API associated with the permission is not enabled.

`primary_permission`

`string`

The preferred name for this permission. If present, then this permission is an alias of, and equivalent to, the listed primary\_permission.

## CustomRolesSupportLevel

The state of the permission with regards to custom roles.

Enums

`SUPPORTED`

Default state. Permission is fully supported for custom role use.

`TESTING`

Permission is being tested to check custom role compatibility.

`NOT_SUPPORTED`

Permission is not supported for custom role use.

## PermissionLaunchStage

A stage representing a permission's lifecycle phase.

Enums

`ALPHA`

The permission is currently in an alpha phase.

`BETA`

The permission is currently in a beta phase.

`GA`

The permission is generally available.

`DEPRECATED`

The permission is being deprecated.

## QueryAuditableServicesRequest

A request to get the list of auditable services for a resource.

Fields

`full_resource_name`

`string`

Required. The full resource name to query from the list of auditable services.

The name follows the Google Cloud Platform resource format. For example, a Cloud Platform project with id `my-project` will be named `//cloudresourcemanager.googleapis.com/projects/my-project` .

## QueryAuditableServicesResponse

A response containing a list of auditable services for a resource.

Fields

`services[]`

`  AuditableService  `

The auditable services for a resource.

## AuditableService

Contains information about an auditable service.

Fields

`name`

`string`

Public name of the service. For example, the service name for IAM is 'iam.googleapis.com'.

## QueryGrantableRolesRequest

The grantable role query request.

Fields

`full_resource_name`

`string`

Required. Required. The full resource name to query from the list of grantable roles.

The name follows the Google Cloud Platform resource format. For example, a Cloud Platform project with id `my-project` will be named `//cloudresourcemanager.googleapis.com/projects/my-project` .

`view`

`  RoleView  `

`page_size`

`int32`

Optional limit on the number of roles to include in the response.

The default is 300, and the maximum is 2,000.

`page_token`

`string`

Optional pagination token returned in an earlier QueryGrantableRolesResponse.

## QueryGrantableRolesResponse

The grantable role query response.

Fields

`roles[]`

`  Role  `

The list of matching roles.

`next_page_token`

`string`

To retrieve the next page of results, set `QueryGrantableRolesRequest.page_token` to this value.

## QueryTestablePermissionsRequest

A request to get permissions which can be tested on a resource.

Fields

`full_resource_name`

`string`

Required. The full resource name to query from the list of testable permissions.

The name follows the Google Cloud Platform resource format. For example, a Cloud Platform project with id `my-project` will be named `//cloudresourcemanager.googleapis.com/projects/my-project` .

`page_size`

`int32`

Optional limit on the number of permissions to include in the response.

The default is 100, and the maximum is 1,000.

`page_token`

`string`

Optional pagination token returned in an earlier QueryTestablePermissionsRequest.

## QueryTestablePermissionsResponse

The response containing permissions which can be tested on a resource.

Fields

`permissions[]`

`  Permission  `

The Permissions testable on the requested resource.

`next_page_token`

`string`

To retrieve the next page of results, set `QueryTestableRolesRequest.page_token` to this value.

## Role

A role in the Identity and Access Management API.

Fields

`name`

`string`

The name of the role.

When `Role` is used in `CreateRole` , the role name must not be set.

When `Role` is used in output and other input such as `UpdateRole` , the role name is the complete path. For example, `roles/logging.viewer` for predefined roles, `organizations/{ORGANIZATION_ID}/roles/myRole` for organization-level custom roles, and `projects/{PROJECT_ID}/roles/myRole` for project-level custom roles.

`title`

`string`

Optional. A human-readable title for the role. Typically this is limited to 100 UTF-8 bytes.

`description`

`string`

Optional. A human-readable description for the role.

`included_permissions[]`

`string`

The names of the permissions this role grants when bound in an IAM policy.

`stage`

`  RoleLaunchStage  `

The current launch stage of the role. If the `ALPHA` launch stage has been selected for a role, the `stage` field will not be included in the returned definition for the role.

`etag`

`bytes`

Used to perform a consistent read-modify-write.

`deleted`

`bool`

The current deleted state of the role. This field is read only. It will be ignored in calls to CreateRole and UpdateRole.

## RoleLaunchStage

A stage representing a role's lifecycle phase.

Enums

`ALPHA`

The user has indicated this role is currently in an Alpha phase. If this launch stage is selected, the `stage` field will not be included when requesting the definition for a given role.

`BETA`

The user has indicated this role is currently in a Beta phase.

`GA`

The user has indicated this role is generally available.

`DEPRECATED`

The user has indicated this role is being deprecated.

`DISABLED`

This role is disabled and will not contribute permissions to any principals it is granted to in policies.

`EAP`

The user has indicated this role is currently in an EAP phase.

## RoleView

A view for Role objects.

Enums

`BASIC`

Omits the `included_permissions` field. This is the default value.

`FULL`

Returns all fields.

## ServiceAccount

An IAM service account.

A service account is an account for an application or a virtual machine (VM) instance, not a person. You can use a service account to call Google APIs. To learn more, read the [overview of service accounts](https://cloud.google.com/iam/help/service-accounts/overview) .

When you create a service account, you specify the project ID that owns the service account, as well as a name that must be unique within the project. IAM uses these values to create an email address that identifies the service account. //

Fields

`name`

`string`

The resource name of the service account.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

`project_id`

`string`

Output only. The ID of the project that owns the service account.

`unique_id`

`string`

Output only. The unique, stable numeric ID for the service account.

Each service account retains its unique ID even if you delete the service account. For example, if you delete a service account, then create a new service account with the same name, the new service account has a different unique ID than the deleted service account.

`email`

`string`

Output only. The email address of the service account.

`display_name`

`string`

Optional. A user-specified, human-readable name for the service account. The maximum length is 100 UTF-8 bytes.

` etag (deprecated)  `

`bytes`

> This item is deprecated\!

Deprecated. Do not use.

`description`

`string`

Optional. A user-specified, human-readable description of the service account. The maximum length is 256 UTF-8 bytes.

`oauth2_client_id`

`string`

Output only. The OAuth 2.0 client ID for the service account.

`disabled`

`bool`

Output only. Whether the service account is disabled.

## ServiceAccountKey

Represents a service account key.

A service account has two sets of key-pairs: user-managed, and system-managed.

User-managed key-pairs can be created and deleted by users. Users are responsible for rotating these keys periodically to ensure security of their service accounts. Users retain the private key of these key-pairs, and Google retains ONLY the public key.

System-managed keys are automatically rotated by Google, and are used for signing for a maximum of two weeks. The rotation process is probabilistic, and usage of the new key will gradually ramp up and down over the key's lifetime.

If you cache the public key set for a service account, we recommend that you update the cache every 15 minutes. User-managed keys can be added and removed at any time, so it is important to update the cache frequently. For Google-managed keys, Google will publish a key at least 6 hours before it is first used for signing and will keep publishing it for at least 6 hours after it was last used for signing.

Public keys for all service accounts are also published at the OAuth2 Service Account API.

Fields

`name`

`string`

The resource name of the service account key in the following format `projects/{PROJECT_ID}/serviceAccounts/{ACCOUNT}/keys/{key}` .

`private_key_type`

`  ServiceAccountPrivateKeyType  `

The output format for the private key. Only provided in `CreateServiceAccountKey` responses, not in `GetServiceAccountKey` or `ListServiceAccountKey` responses.

Google never exposes system-managed private keys, and never retains user-managed private keys.

`key_algorithm`

`  ServiceAccountKeyAlgorithm  `

Specifies the algorithm (and possibly key size) for the key.

`private_key_data`

`bytes`

The private key data. Only provided in `CreateServiceAccountKey` responses. Make sure to keep the private key data secure because it allows for the assertion of the service account identity. When base64 decoded, the private key data can be used to authenticate with Google API client libraries and with [gcloud auth activate-service-account](https://docs.cloud.google.com/sdk/gcloud/reference/auth/activate-service-account) .

`public_key_data`

`bytes`

The public key data. Only provided in `GetServiceAccountKey` responses.

`valid_after_time`

`  Timestamp  `

The key can be used after this timestamp.

`valid_before_time`

`  Timestamp  `

The key can be used before this timestamp. For system-managed key pairs, this timestamp is the end time for the private key signing operation. The public key could still be used for verification for a few hours after this time.

`key_origin`

`  ServiceAccountKeyOrigin  `

The key origin.

`key_type`

`  KeyType  `

The key type.

`disabled`

`bool`

The key status.

`disable_reason`

`  ServiceAccountKeyDisableReason  `

Output only. optional. If the key is disabled, it may have a DisableReason describing why it was disabled.

`extended_status[]`

`  ExtendedStatus  `

Output only. Extended Status provides permanent information about a service account key. For example, if this key was detected as exposed or compromised, that information will remain for the lifetime of the key in the extended\_status.

## ExtendedStatus

Extended status can store additional metadata. For example, for keys disabled due to their private key data being expoesed we may include a message with more information about the exposure.

Fields

`key`

`  ServiceAccountKeyExtendedStatusKey  `

The key for this extended status.

`value`

`string`

The value for the extended status.

## ServiceAccountKeyAlgorithm

Supported key algorithms.

Enums

`KEY_ALG_UNSPECIFIED`

An unspecified key algorithm.

`KEY_ALG_RSA_1024`

1k RSA Key.

`KEY_ALG_RSA_2048`

2k RSA Key.

## ServiceAccountKeyDisableReason

DisableReason is intended to communicate more information about a disabled Service Accounts or Service Account Key.

Enums

`SERVICE_ACCOUNT_KEY_DISABLE_REASON_UNSPECIFIED`

Unspecified disable reason

`SERVICE_ACCOUNT_KEY_DISABLE_REASON_USER_INITIATED`

Disabled by the user

`SERVICE_ACCOUNT_KEY_DISABLE_REASON_EXPOSED`

Google detected this Service Account external key's private key data as exposed, typically in a public repository on GitHub or similar.

`SERVICE_ACCOUNT_KEY_DISABLE_REASON_COMPROMISE_DETECTED`

This service account external key was detected as compromised and used by an attacker.

## ServiceAccountKeyExtendedStatusKey

Different categories of extended\_status messages. For example the accompanying message for SERVICE\_ACCOUNT\_KEY\_EXTENDED\_STATUS\_KEY\_EXPOSED may contain information about how the key was exposed.

Enums

`SERVICE_ACCOUNT_KEY_EXTENDED_STATUS_KEY_UNSPECIFIED`

Unspecified extended status, should not be used.

`SERVICE_ACCOUNT_KEY_EXTENDED_STATUS_KEY_EXPOSED`

This key has been detected as exposed. extended\_status\_value may contain information about the exposure (public GitHub repo, open internet, etc.)

`SERVICE_ACCOUNT_KEY_EXTENDED_STATUS_KEY_COMPROMISE_DETECTED`

This key was implicated in a compromise or other attack. extended\_status\_value may contain information about the abuse perpetrated.

## ServiceAccountKeyOrigin

Service Account Key Origin.

Enums

`ORIGIN_UNSPECIFIED`

Unspecified key origin.

`USER_PROVIDED`

Key is provided by user.

`GOOGLE_PROVIDED`

Key is provided by Google.

## ServiceAccountPrivateKeyType

Supported private key output formats.

Enums

`TYPE_UNSPECIFIED`

Unspecified. Equivalent to `TYPE_GOOGLE_CREDENTIALS_FILE` .

`TYPE_PKCS12_FILE`

PKCS12 format. The password for the PKCS12 file is `notasecret` . For more information, see <https://tools.ietf.org/html/rfc7292> .

`TYPE_GOOGLE_CREDENTIALS_FILE`

Google Credentials File format.

## ServiceAccountPublicKeyType

Supported public key output formats.

Enums

`TYPE_NONE`

Do not return the public key.

`TYPE_X509_PEM_FILE`

X509 PEM format.

`TYPE_RAW_PUBLIC_KEY`

Raw public key.

## SignBlobRequest

Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The service account sign blob request.

Fields

` name (deprecated)  `

`string`

> This item is deprecated\!

Required. Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The resource name of the service account.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccounts.signBlob`

` bytes_to_sign (deprecated)  `

`bytes`

> This item is deprecated\!

Required. Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The bytes to sign.

## SignBlobResponse

Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The service account sign blob response.

Fields

` key_id (deprecated)  `

`string`

> This item is deprecated\!

Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The id of the key used to sign the blob.

` signature (deprecated)  `

`bytes`

> This item is deprecated\!

Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The signed blob.

## SignJwtRequest

Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The service account sign JWT request.

Fields

` name (deprecated)  `

`string`

> This item is deprecated\!

Required. Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The resource name of the service account.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccounts.signJwt`

` payload (deprecated)  `

`string`

> This item is deprecated\!

Required. Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The JWT payload to sign. Must be a serialized JSON object that contains a JWT Claims Set. For example: `{"sub": "user@example.com", "iat": 313435}`

If the JWT Claims Set contains an expiration time ( `exp` ) claim, it must be an integer timestamp that is not in the past and no more than 12 hours in the future.

If the JWT Claims Set does not contain an expiration time ( `exp` ) claim, this claim is added automatically, with a timestamp that is 1 hour in the future.

## SignJwtResponse

Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The service account sign JWT response.

Fields

` key_id (deprecated)  `

`string`

> This item is deprecated\!

Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The id of the key used to sign the JWT.

` signed_jwt (deprecated)  `

`string`

> This item is deprecated\!

Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The signed JWT.

## UndeleteOauthClientRequest

Request message for UndeleteOauthClient.

Fields

`name`

`string`

Required. The name of the `  OauthClient  ` to undelete.

Format: `projects/{project}/locations/{location}/oauthClients/{oauth_client}` .

## UndeleteRoleRequest

The request to undelete an existing role.

Fields

`name`

`string`

The `name` parameter's value depends on the target resource for the request, namely [projects](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles) or [organizations](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles) . Each resource type's `name` value format is described below:

  - [projects.roles.undelete](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/undelete) : `projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}` . This method undeletes only [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) that have been created at the project level. Example request URL: `https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}`

  - [organizations.roles.undelete](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/undelete) : `organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}` . This method undeletes only [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) that have been created at the organization level. Example request URL: `https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}`

Note: Wildcard (\*) values are invalid; you must specify a complete project ID or organization ID.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.roles.undelete`

`etag`

`bytes`

Used to perform a consistent read-modify-write.

## UndeleteServiceAccountRequest

The service account undelete request.

Fields

`name`

`string`

The resource name of the service account.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccounts.undelete`

## UndeleteServiceAccountResponse

Fields

`restored_account`

`  ServiceAccount  `

Metadata for the restored service account.

## UndeleteWorkforcePoolProviderKeyRequest

Request message for UndeleteWorkforcePoolProviderKey.

Fields

`name`

`string`

Required. The name of the key to undelete.

## UndeleteWorkforcePoolProviderRequest

Request message for UndeleteWorkforcePoolProvider.

Fields

`name`

`string`

Required. The name of the provider to undelete.

Format: `locations/{location}/workforcePools/{workforce_pool_id}/providers/{provider_id}`

## UndeleteWorkforcePoolProviderScimTenantRequest

Gemini Enterprise only. Request message for UndeleteWorkforcePoolProviderScimTenant.

Fields

`name`

`string`

Required. Gemini Enterprise only. The name of the SCIM tenant to undelete.

Format: `locations/{location}/workforcePools/{workforce_pool}/providers/{provider}/scimTenants/{scim_tenant}`

## UndeleteWorkforcePoolProviderScimTokenRequest

Gemini Enterprise only. Request message for UndeleteWorkforcePoolProviderScimToken.

Fields

`name`

`string`

Required. Gemini Enterprise only. The name of the SCIM token to undelete.

Format: `locations/{location}/workforcePools/{workforce_pool}/providers/{provider}/scimTenants/{scim_tenant}/tokens/{token}`

## UndeleteWorkforcePoolRequest

Request message for UndeleteWorkforcePool.

Fields

`name`

`string`

Required. The name of the pool to undelete.

Format: `locations/{location}/workforcePools/{workforce_pool_id}`

## UndeleteWorkforcePoolSubjectRequest

Request message for \[UndeleteWorkforcePoolSubject\]\[\].

Fields

`name`

`string`

Required. The resource name of the `  WorkforcePoolSubject  ` . Special characters, like `/` and `:` , must be escaped, because all URLs need to conform to the "When to Escape and Unescape" section of [RFC3986](https://www.ietf.org/rfc/rfc2396.txt) .

Format: `locations/{location}/workforcePools/{workforce_pool_id}/subjects/{subject_id}`

## UpdateOauthClientCredentialRequest

Request message for UpdateOauthClientCredential.

Fields

`oauth_client_credential`

`  OauthClientCredential  `

Required. The `  OauthClientCredential  ` to update. The `name` field is used to identify the `  OauthClientCredential  ` .

`update_mask`

`  FieldMask  `

Required. The list of fields to update.

## UpdateOauthClientRequest

Request message for UpdateOauthClient.

Fields

`oauth_client`

`  OauthClient  `

Required. The `  OauthClient  ` to update. The `name` field is used to identify the `  OauthClient  ` .

`update_mask`

`  FieldMask  `

Required. The list of fields to update.

## UpdateRoleRequest

The request to update a role.

Fields

`name`

`string`

The `name` parameter's value depends on the target resource for the request, namely [projects](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles) or [organizations](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles) . Each resource type's `name` value format is described below:

  - [projects.roles.patch](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/patch) : `projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}` . This method updates only [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) that have been created at the project level. Example request URL: `https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}`

  - [organizations.roles.patch](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/patch) : `organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}` . This method updates only [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) that have been created at the organization level. Example request URL: `https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}`

Note: Wildcard (\*) values are invalid; you must specify a complete project ID or organization ID.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.roles.update`

`role`

`  Role  `

The updated role.

`update_mask`

`  FieldMask  `

A mask describing which fields in the Role have changed.

## UpdateWorkforcePoolProviderRequest

Request message for UpdateWorkforcePoolProvider.

Fields

`workforce_pool_provider`

`  WorkforcePoolProvider  `

Required. The provider to update.

`update_mask`

`  FieldMask  `

Required. The list of fields to update.

## UpdateWorkforcePoolProviderScimTenantRequest

Gemini Enterprise only. Request message for UpdateWorkforcePoolProviderScimTenant.

Fields

`workforce_pool_provider_scim_tenant`

`  WorkforcePoolProviderScimTenant  `

Required. Gemini Enterprise only. The SCIM tenant to update. The `name` field is used to identify the SCIM tenant.

`update_mask`

`  FieldMask  `

Optional. Gemini Enterprise only. The list of fields to update.

## UpdateWorkforcePoolProviderScimTokenRequest

Gemini Enterprise only. Request message for UpdateWorkforcePoolProviderScimToken.

Fields

`workforce_pool_provider_scim_token`

`  WorkforcePoolProviderScimToken  `

Required. Gemini Enterprise only. The SCIM token to update. The `name` field is used to identify the SCIM token.

`update_mask`

`  FieldMask  `

Optional. Gemini Enterprise only. The list of fields to update.

## UpdateWorkforcePoolRequest

Request message for UpdateWorkforcePool.

Fields

`workforce_pool`

`  WorkforcePool  `

Required. The pool to update. The `name` field is used to identify the pool.

`update_mask`

`  FieldMask  `

Required. The list of fields to update.

## UploadServiceAccountKeyRequest

The service account key upload request.

Fields

`name`

`string`

The resource name of the service account key.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccountKeys.create`

`public_key_data`

`bytes`

The public key to associate with the service account. Must be an RSA public key that is wrapped in an X.509 v3 certificate. Include the first line, `-----BEGIN CERTIFICATE-----` , and the last line, `-----END CERTIFICATE-----` .

## WorkforcePool

Represents a collection of external workforces. Provides namespaces for federated users that can be referenced in IAM policies.

Fields

`name`

`string`

Identifier. The resource name of the pool.

Format: `locations/{location}/workforcePools/{workforce_pool_id}`

`parent`

`string`

Immutable. The resource name of the parent.

Format: `organizations/{org-id}` .

`display_name`

`string`

Optional. A display name for the pool.

Cannot exceed 32 characters.

`description`

`string`

Optional. A description of the pool.

Cannot exceed 256 characters.

`state`

`  State  `

Output only. The state of the pool.

`disabled`

`bool`

Optional. Disables the workforce pool. You cannot use a disabled pool to exchange tokens, or use existing tokens to access resources. If the pool is re-enabled, existing tokens grant access again.

`session_duration`

`  Duration  `

Optional. Duration that the Google Cloud access tokens, console sign-in sessions, and `gcloud` sign-in sessions from this pool are valid.

Must be greater than 15 minutes (900s) and less than 12 hours (43200s). If `session_duration` is not configured, minted credentials have a default duration of one hour (3600s).

For SAML providers, the lifetime of the token is the minimum of the `session_duration` and the `SessionNotOnOrAfter` claim in the SAML assertion.

`expire_time`

`  Timestamp  `

Output only. Time after which the workforce pool will be permanently purged and cannot be recovered.

`access_restrictions`

`  AccessRestrictions  `

Optional. Configure access restrictions on the workforce pool users. This is an optional field. If specified web sign-in can be restricted to given set of services or programmatic sign-in can be disabled for pool users.

## AccessRestrictions

Access related restrictions on the workforce pool.

Fields

`allowed_services[]`

`  ServiceConfig  `

Optional. Immutable. Services allowed for web sign-in with the workforce pool. If not set by default there are no restrictions.

`disable_programmatic_signin`

`bool`

Optional. Disable programmatic sign-in by disabling token issue via the Security Token API endpoint. See [Security Token Service API](https://cloud.google.com/iam/docs/reference/sts/rest) .

## ServiceConfig

Configuration for a service.

Fields

`domain`

`string`

Optional. Domain name of the service.

Example: console.cloud.google

## State

The current state of the pool.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The pool is active and may be used in Google Cloud policies.

`DELETED`

The pool is soft-deleted. Soft-deleted pools are permanently deleted after approximately 30 days. You can restore a soft-deleted pool using `  UndeleteWorkforcePool  ` .

You cannot reuse the ID of a soft-deleted pool until it is permanently deleted.

While a pool is deleted, you cannot use it to exchange tokens, or use existing tokens to access resources. If the pool is undeleted, existing tokens grant access again.

## WorkforcePoolOperationMetadata

This type has no fields.

Metadata for long-running WorkforcePool operations.

## WorkforcePoolProvider

A configuration for an external identity provider.

Fields

`name`

`string`

Identifier. The resource name of the provider.

Format: `locations/{location}/workforcePools/{workforce_pool_id}/providers/{provider_id}`

`display_name`

`string`

Optional. A display name for the provider.

Cannot exceed 32 characters.

`description`

`string`

Optional. A description of the provider. Cannot exceed 256 characters.

`state`

`  State  `

Output only. The state of the provider.

`disabled`

`bool`

Optional. Disables the workforce pool provider. You cannot use a disabled provider to exchange tokens. However, existing tokens still grant access.

`attribute_mapping`

`map<string, string>`

Required. Maps attributes from the authentication credentials issued by an external identity provider to Google Cloud attributes, such as `subject` and `segment` .

Each key must be a string specifying the Google Cloud IAM attribute to map to.

The following keys are supported:

  - `google.subject` : The principal IAM is authenticating. You can reference this value in IAM bindings. This is also the subject that appears in Cloud Logging logs. This is a required field and the mapped subject cannot exceed 127 bytes.

  - `google.groups` : Groups the authenticating user belongs to. You can grant groups access to resources using an IAM `principalSet` binding; access applies to all members of the group.

  - `google.display_name` : The name of the authenticated user. This is an optional field and the mapped display name cannot exceed 100 bytes. If not set, `google.subject` will be displayed instead. This attribute cannot be referenced in IAM bindings.

  - `google.profile_photo` : The URL that specifies the authenticated user's thumbnail photo. This is an optional field. When set, the image will be visible as the user's profile picture. If not set, a generic user icon will be displayed instead. This attribute cannot be referenced in IAM bindings.

  - `google.posix_username` : The Linux username used by OS Login. This is an optional field and the mapped POSIX username cannot exceed 32 characters. The key must match the regex `^[a-zA-Z0-9._][a-zA-Z0-9._-]{0,31}$` . This attribute cannot be referenced in IAM bindings.

You can also provide custom attributes by specifying `attribute.{custom_attribute}` , where {custom\_attribute} is the name of the custom attribute to be mapped. You can define a maximum of 50 custom attributes. The maximum length of a mapped attribute key is 100 characters, and the key may only contain the characters `[a-z0-9_]` .

You can reference these attributes in IAM policies to define fine-grained access for a workforce pool to Google Cloud resources. For example:

  - `google.subject` : `principal://iam.googleapis.com/locations/global/workforcePools/{pool}/subject/{value}`

  - `google.groups` : `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool}/group/{value}`

  - `attribute.{custom_attribute}` : `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool}/attribute.{custom_attribute}/{value}`

Each value must be a [Common Expression Language](https://opensource.google/projects/cel) function that maps an identity provider credential to the normalized attribute specified by the corresponding map key.

You can use the `assertion` keyword in the expression to access a JSON representation of the authentication credential issued by the provider.

The maximum length of an attribute mapping expression is 2048 characters. When evaluated, the total size of all mapped attributes must not exceed 16 KB.

For OIDC providers, you must supply a custom mapping that includes the `google.subject` attribute. For example, the following maps the `sub` claim of the incoming credential to the `subject` attribute on a Google token:

    {"google.subject": "assertion.sub"}

`attribute_condition`

`string`

Optional. A [Common Expression Language](https://opensource.google/projects/cel) expression, in plain text, to restrict what otherwise valid authentication credentials issued by the provider should not be accepted.

The expression must output a boolean representing whether to allow the federation.

The following keywords may be referenced in the expressions:

  - `assertion` : JSON representing the authentication credential issued by the provider.
  - `google` : The Google attributes mapped from the assertion in the `attribute_mappings` . `google.profile_photo` , `google.display_name` and `google.posix_username` are not supported.
  - `attribute` : The custom attributes mapped from the assertion in the `attribute_mappings` .

The maximum length of the attribute condition expression is 4096 characters. If unspecified, all valid authentication credentials will be accepted.

The following example shows how to only allow credentials with a mapped `google.groups` value of `admins` :

    "'admins' in google.groups"

`expire_time`

`  Timestamp  `

Output only. Time after which the workforce identity pool provider will be permanently purged and cannot be recovered.

`extra_attributes_oauth2_client`

`  ExtraAttributesOAuth2Client  `

Optional. The configuration for OAuth 2.0 client used to get the additional user attributes. This should be used when users can't get the desired claims in authentication credentials. Currently, this configuration is only supported with OIDC protocol.

`detailed_audit_logging`

`bool`

Optional. If true, populates additional debug information in Cloud Audit Logs for this provider. Logged attribute mappings and values can be found in `sts.googleapis.com` data access logs. Default value is false.

`extended_attributes_oauth2_client`

`  ExtraAttributesOAuth2Client  `

Optional. The configuration for OAuth 2.0 client used to get the extended group memberships for user identities. Only the `AZURE_AD_GROUPS_ID` attribute type is supported. Extended groups supports a subset of Google Cloud services. When the user accesses these services, extended group memberships override the mapped `google.groups` attribute. Extended group memberships cannot be used in attribute mapping or attribute condition expressions.

To keep extended group memberships up to date, extended groups are retrieved when the user signs in and at regular intervals during the user's active session. Each user identity in the workforce identity pool must map to a unique Microsoft Entra ID user.

`scim_usage`

`  ScimUsage  `

Optional. Gemini Enterprise only. Specifies whether the workforce identity pool provider uses SCIM-managed groups instead of the `google.groups` attribute mapping for authorization checks.

The `scim_usage` and `extended_attributes_oauth2_client` fields are mutually exclusive. A request that enables both fields on the same workforce identity pool provider will produce an error.

Union field `provider_config` .

`provider_config` can be only one of the following:

`saml`

`  Saml  `

A SAML identity provider configuration.

`oidc`

`  Oidc  `

An OpenID Connect 1.0 identity provider configuration.

## ExtraAttributesOAuth2Client

Represents the OAuth 2.0 client credential configuration for retrieving additional user attributes that are not present in the initial authentication credentials from the identity provider, for example, groups. See <https://datatracker.ietf.org/doc/html/rfc6749#section-4.4> for more details on client credentials grant flow.

Fields

`issuer_uri`

`string`

Required. The OIDC identity provider's issuer URI. Must be a valid URI using the `https` scheme. Required to get the OIDC discovery document.

`client_id`

`string`

Required. The OAuth 2.0 client ID for retrieving extra attributes from the identity provider. Required to get the Access Token using client credentials grant flow.

`client_secret`

`  ClientSecret  `

Required. The OAuth 2.0 client secret for retrieving extra attributes from the identity provider. Required to get the Access Token using client credentials grant flow.

`attributes_type`

`  AttributesType  `

Required. Represents the IdP and type of claims that should be fetched.

`query_parameters`

`  QueryParameters  `

Optional. Represents the parameters to control which claims are fetched from an IdP.

## AttributesType

Represents the IdP and type of claims that should be fetched.

Enums

`ATTRIBUTES_TYPE_UNSPECIFIED`

No AttributesType specified.

`AZURE_AD_GROUPS_MAIL`

Used to get the user's group claims from the Microsoft Entra ID identity provider using the configuration provided in `ExtraAttributesOAuth2Client` . The `mail` property of the `microsoft.graph.group` object is used for claim mapping. For more information about `microsoft.graph.group` properties, see <https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0#properties> . The group mail addresses of the user's groups that are returned from Microsoft Entra ID can be mapped by using the following attributes:

  - OIDC: `assertion.groups`
  - SAML: `assertion.attributes.groups`

`AZURE_AD_GROUPS_ID`

Used to get the user's group claims from the Microsoft Entra ID identity provider using the configuration provided in `ExtraAttributesOAuth2Client` . The `id` property of the `microsoft.graph.group` object is used for claim mapping. For more information about `microsoft.graph.group` properties, see <https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0#properties> . The group IDs of the user's groups that are returned from Microsoft Entra ID can be mapped by using the following attributes:

  - OIDC: `assertion.groups`
  - SAML: `assertion.attributes.groups`

`AZURE_AD_GROUPS_DISPLAY_NAME`

Used to get the user's group claims from the Microsoft Entra ID identity provider using the configuration provided in `ExtraAttributesOAuth2Client` . The `displayName` property of the `microsoft.graph.group` object is used for claim mapping. For more information about `microsoft.graph.group` properties, see <https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0#properties> . The group displayNames of the user's groups that are returned from Microsoft Entra ID can be mapped by using the following attributes:

  - OIDC: `assertion.groups`
  - SAML: `assertion.attributes.groups`

## QueryParameters

Represents the parameters to control which claims are fetched from an IdP.

Fields

`filter`

`string`

Optional. The filter used to request specific records from the IdP. By default, all of the groups that are associated with a user are fetched. For Microsoft Entra ID, you can add `$search` query parameters using [Keyword Query Language](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/keyword-query-language-kql-syntax-reference) . To learn more about `$search` querying in Microsoft Entra ID, see [Use the `$search` query parameter](https://learn.microsoft.com/en-us/graph/search-query-parameter) .

Additionally, Workforce Identity Federation automatically adds the following [`$filter` query parameters](https://learn.microsoft.com/en-us/graph/filter-query-parameter) , based on the value of `attributes_type` . Values passed to `filter` are converted to `$search` query parameters. Additional `$filter` query parameters cannot be added using this field.

  - `AZURE_AD_GROUPS_MAIL` : `mailEnabled` and `securityEnabled` filters are applied.
  - `AZURE_AD_GROUPS_ID` : `securityEnabled` filter is applied.
  - `AZURE_AD_GROUPS_DISPLAY_NAME` : `securityEnabled` filter is applied.

## Oidc

Represents an OpenID Connect 1.0 identity provider.

Fields

`issuer_uri`

`string`

Required. The OIDC issuer URI. Must be a valid URI using the `https` scheme.

`client_id`

`string`

Required. The client ID. Must match the audience claim of the JWT issued by the identity provider.

`client_secret`

`  ClientSecret  `

Optional. The optional client secret. Required to enable Authorization Code flow for web sign-in.

`web_sso_config`

`  WebSsoConfig  `

Required. Configuration for web single sign-on for the OIDC provider. Here, web sign-in refers to console sign-in and gcloud sign-in through the browser.

`jwks_json`

`string`

Optional. OIDC JWKs in JSON String format. For details on the definition of a JWK, see <https://tools.ietf.org/html/rfc7517> . If not set, the `jwks_uri` from the discovery document that is fetched from the well-known path of the `issuer_uri` , will be used. RSA and EC asymmetric keys are supported. The JWK must use the following format and include only the following fields: { "keys": \[ { "kty": "RSA/EC", "alg": " ", "use": "sig", "kid": " ", "n": "", "e": "", "x": "", "y": "", "crv": "" } \] }

## ClientSecret

Representation of a client secret configured for the OIDC provider.

Fields

Union field `source` .

`source` can be only one of the following:

`value`

`  Value  `

The value of the client secret.

## Value

Representation of the value of the client secret.

Fields

`plain_text`

`string`

Optional. Input only. The plain text of the client secret value. For security reasons, this field is only used for input and will never be populated in any response.

`thumbprint`

`string`

Output only. A thumbprint to represent the current client secret value.

## WebSsoConfig

Configuration for web single sign-on for the OIDC provider.

Fields

`response_type`

`  ResponseType  `

Required. The Response Type to request for in the OIDC Authorization Request for web sign-in.

The `CODE` Response Type is recommended to avoid the Implicit Flow, for security reasons.

`assertion_claims_behavior`

`  AssertionClaimsBehavior  `

Required. The behavior for how OIDC Claims are included in the `assertion` object used for attribute mapping and attribute condition.

`additional_scopes[]`

`string`

Optional. Additional scopes to request for in the OIDC authentication request on top of scopes requested by default. By default, the `openid` , `profile` and `email` scopes that are supported by the identity provider are requested.

Each additional scope may be at most 256 characters. A maximum of 10 additional scopes may be configured.

## AssertionClaimsBehavior

Possible behaviors for how OIDC Claims are included in the `assertion` object used for attribute mapping and attribute condition.

Enums

`ASSERTION_CLAIMS_BEHAVIOR_UNSPECIFIED`

No assertion claims behavior specified.

`MERGE_USER_INFO_OVER_ID_TOKEN_CLAIMS`

Merge the UserInfo Endpoint Claims with ID Token Claims, preferring UserInfo Claim Values for the same Claim Name. This option is available only for the Authorization Code Flow.

`ONLY_ID_TOKEN_CLAIMS`

Only include ID Token Claims.

## ResponseType

Possible Response Types to request for in the OIDC Authorization Request for web sign-in. This determines the OIDC Authentication Flow. See <https://openid.net/specs/openid-connect-core-1_0.html#Authentication> for a mapping of Response Type to OIDC Authentication Flow.

Enums

`RESPONSE_TYPE_UNSPECIFIED`

No Response Type specified.

`CODE`

The `response_type=code` selection uses the Authorization Code Flow for web sign-in. Requires a configured client secret.

`ID_TOKEN`

The `response_type=id_token` selection uses the Implicit Flow for web sign-in.

## Saml

Represents a SAML identity provider.

Fields

Union field `identity_provider` .

`identity_provider` can be only one of the following:

`idp_metadata_xml`

`string`

Required. SAML Identity provider configuration metadata xml doc. The xml document should comply with [SAML 2.0 specification](https://docs.oasis-open.org/security/saml/v2.0/saml-metadata-2.0-os.pdf) . The max size of the acceptable xml document will be bounded to 128k characters.

The metadata xml document should satisfy the following constraints: 1) Must contain an Identity Provider Entity ID. 2) Must contain at least one non-expired signing key certificate. 3) For each signing key: a) Valid from should be no more than 7 days from now. b) Valid to should be no more than 25 years in the future. 4) Up to 3 IdP signing keys are allowed in the metadata xml.

When updating the provider's metadata xml, at least one non-expired signing key must overlap with the existing metadata. This requirement is skipped if there are no non-expired signing keys present in the existing metadata.

## ScimUsage

Gemini Enterprise only. Specifies whether the workforce identity pool provider uses SCIM-managed groups.

Enums

`SCIM_USAGE_UNSPECIFIED`

Gemini Enterprise only. Do not use SCIM data.

`ENABLED_FOR_GROUPS`

Gemini Enterprise only. SCIM sync is enabled and SCIM-managed groups are used for authorization checks.

## State

The current state of the provider.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The provider is active and may be used to validate authentication credentials.

`DELETED`

The provider is soft-deleted. Soft-deleted providers are permanently deleted after approximately 30 days. You can restore a soft-deleted provider using `  UndeleteWorkforcePoolProvider  ` .

## WorkforcePoolProviderKey

Represents a public key configuration for a Workforce Pool Provider. The key can be configured in your identity provider to encrypt SAML assertions. Google holds the corresponding private key, which it uses to decrypt encrypted tokens.

Fields

`name`

`string`

Identifier. The resource name of the key.

Format: `locations/{location}/workforcePools/{workforce_pool_id}/providers/{provider_id}/keys/{key_id}`

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

Output only. The time after which the key will be permanently deleted and cannot be recovered. Note that the key may get purged before this time if the total limit of keys per provider is exceeded.

## KeyUse

The purpose of the key.

Enums

`KEY_USE_UNSPECIFIED`

KeyUse unspecified. Do not use. The purpose of the key must be specified.

`ENCRYPTION`

The key is used for encryption.

## State

The current state of the key.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The key is active.

`DELETED`

The key is soft-deleted. Soft-deleted keys are permanently deleted after approximately 30 days. You can restore a soft-deleted key using `  UndeleteWorkforcePoolProviderKey  ` .

## WorkforcePoolProviderKeyOperationMetadata

This type has no fields.

Metadata for long-running WorkforcePoolProviderKey operations.

## WorkforcePoolProviderOperationMetadata

This type has no fields.

Metadata for long-running WorkforcePoolProvider operations.

## WorkforcePoolProviderScimTenant

Gemini Enterprise only. Represents a SCIM tenant. Used for provisioning and managing identity data (such as Users and Groups) in cross-domain environments.

Fields

`name`

`string`

Identifier. Gemini Enterprise only. The resource name of the SCIM Tenant.

Format: `locations/{location}/workforcePools/{workforce_pool}/providers/ {workforce_pool_provider}/scimTenants/{scim_tenant}`

`base_uri`

`string`

Output only. Gemini Enterprise only. Represents the base URI as defined in [RFC 7644, Section 1.3](https://datatracker.ietf.org/doc/html/rfc7644#section-1.3) . Clients must use this as the root address for managing resources under the tenant.

Format: [https://iamscim.googleapis.com/{version}/{tenant\_id}/](https://iamscim.googleapis.com/%7Bversion%7D/%7Btenant_id%7D/)

`state`

`  State  `

Output only. Gemini Enterprise only. The state of the tenant.

`description`

`string`

Optional. Gemini Enterprise only. The description of the SCIM tenant.

Cannot exceed 256 characters.

`display_name`

`string`

Optional. Gemini Enterprise only. The display name of the SCIM tenant.

Cannot exceed 32 characters.

`claim_mapping`

`map<string, string>`

Required. Immutable. Gemini Enterprise only. Maps SCIM attributes to Google attributes.

This mapping is used to associate the attributes synced via SCIM with the Google Cloud attributes used in IAM policies for Workforce Identity Federation. SCIM-managed user and group attributes are mapped to `google.subject` and `google.group` respectively.

Each key must be a string specifying the Google Cloud IAM attribute to map to. The supported keys are as follows:

  - `google.subject` : The principal IAM is authenticating. You can reference this value in IAM bindings. This is also the subject that appears in Cloud Logging logs. This is a required field and the mapped subject cannot exceed 127 bytes.

  - `google.group` : Group the authenticating user belongs to. You can grant group access to resources using an IAM `principalSet` binding; access applies to all members of the group.

Each value must be a [Common Expression Language](https://opensource.google/projects/cel) expression that maps SCIM user or group attribute to the normalized attribute specified by the corresponding map key.

Example: To map the SCIM user's `externalId` to `google.subject` and the SCIM group's `externalId` to `google.group` :

    {
      "google.subject": "user.externalId",
      "google.group": "group.externalId"
    }

`purge_time`

`  Timestamp  `

Output only. Gemini Enterprise only. The timestamp that represents the time when the SCIM tenant is purged.

`service_agent`

`string`

Output only. Service Agent created by SCIM Tenant API. SCIM tokens created under this tenant will be attached to this service agent.

## State

Gemini Enterprise only. The current state of the SCIM tenant.

Enums

`STATE_UNSPECIFIED`

Gemini Enterprise only. State unspecified.

`ACTIVE`

Gemini Enterprise only. The tenant is active and may be used to provision users and groups.

`DELETED`

Gemini Enterprise only. The tenant is soft-deleted. Soft-deleted tenants are permanently deleted after approximately 30 days.

## WorkforcePoolProviderScimToken

Gemini Enterprise only. Represents a token for the `  WorkforcePoolProviderScimTenant  ` . Used for authenticating SCIM provisioning requests.

Fields

`name`

`string`

Identifier. Gemini Enterprise only. The resource name of the SCIM Token.

Format: `locations/{location}/workforcePools/{workforce_pool}/providers/ {workforce_pool_provider}/scimTenants/{scim_tenant}/tokens/{token}`

`security_token`

`string`

Output only. Gemini Enterprise only. The token string. Provide this to the IdP for authentication. Will be set only during creation.

`state`

`  State  `

Output only. Gemini Enterprise only. The state of the token.

`display_name`

`string`

Optional. Gemini Enterprise only. The display name of the SCIM token.

Cannot exceed 32 characters.

## State

Gemini Enterprise only. The current state of the SCIM token.

Enums

`STATE_UNSPECIFIED`

Gemini Enterprise only. State unspecified.

`ACTIVE`

Gemini Enterprise only. The token is active and may be used to provision users and groups.

`DELETED`

Gemini Enterprise only. The token is soft-deleted. Soft-deleted tokens are permanently deleted after approximately 30 days.

## WorkforcePoolSubject

Represents a single identity in a Workforce Pool.

Fields

`name`

`string`

Output only. The resource name of the `  WorkforcePoolSubject  ` . Special characters, like `/` and `:` , must be escaped, because all URLs need to conform to the "When to Escape and Unescape" section of [RFC3986](https://www.ietf.org/rfc/rfc2396.txt) .

Format: `locations/{location}/workforcePools/{workforce_pool_id}/subjects/{subject_id}`

`expire_time`

`  Timestamp  `

Output only. The planned hard deletion time of this resource in [RFC3339](https://tools.ietf.org/html/rfc3339) text format.

## WorkforcePoolSubjectOperationMetadata

This type has no fields.

Metadata for long-running `  WorkforcePoolSubject  ` operations.
