---
name: documents/docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta
uri: https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta
title: Package google.iam.v1beta
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

  - `  WorkloadIdentityPools  ` (interface)
  - `  CreateWorkloadIdentityPoolProviderRequest  ` (message)
  - `  CreateWorkloadIdentityPoolRequest  ` (message)
  - `  DeleteWorkloadIdentityPoolProviderRequest  ` (message)
  - `  DeleteWorkloadIdentityPoolRequest  ` (message)
  - `  GetWorkloadIdentityPoolProviderRequest  ` (message)
  - `  GetWorkloadIdentityPoolRequest  ` (message)
  - `  ListWorkloadIdentityPoolProvidersRequest  ` (message)
  - `  ListWorkloadIdentityPoolProvidersResponse  ` (message)
  - `  ListWorkloadIdentityPoolsRequest  ` (message)
  - `  ListWorkloadIdentityPoolsResponse  ` (message)
  - `  UndeleteWorkloadIdentityPoolProviderRequest  ` (message)
  - `  UndeleteWorkloadIdentityPoolRequest  ` (message)
  - `  UpdateWorkloadIdentityPoolProviderRequest  ` (message)
  - `  UpdateWorkloadIdentityPoolRequest  ` (message)
  - `  WorkloadIdentityPool  ` (message)
  - `  WorkloadIdentityPool.State  ` (enum)
  - `  WorkloadIdentityPoolOperationMetadata  ` (message)
  - `  WorkloadIdentityPoolProvider  ` (message)
  - `  WorkloadIdentityPoolProvider.Aws  ` (message)
  - `  WorkloadIdentityPoolProvider.Oidc  ` (message)
  - `  WorkloadIdentityPoolProvider.State  ` (enum)
  - `  WorkloadIdentityPoolProviderOperationMetadata  ` (message)

## WorkloadIdentityPools

Manages WorkloadIdentityPools.

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

Required. The pool to update. The `name` field is used to identify the pool.

`update_mask`

`  FieldMask  `

Required. The list of fields to update.

## WorkloadIdentityPool

Represents a collection of external workload identities. You can define IAM policies to grant these identities access to Google Cloud resources.

Fields

`name`

`string`

Output only. The resource name of the pool.

`display_name`

`string`

A display name for the pool. Cannot exceed 32 characters.

`description`

`string`

A description of the pool. Cannot exceed 256 characters.

`state`

`  State  `

Output only. The state of the pool.

`disabled`

`bool`

Whether the pool is disabled. You cannot use a disabled pool to exchange tokens, or use existing tokens to access resources. If the pool is re-enabled, existing tokens grant access again.

`expire_time`

`  Timestamp  `

Output only. Time after which the workload identity pool will be permanently purged and cannot be recovered.

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

A display name for the provider. Cannot exceed 32 characters.

`description`

`string`

A description for the provider. Cannot exceed 256 characters.

`state`

`  State  `

Output only. The state of the provider.

`disabled`

`bool`

Whether the provider is disabled. You cannot use a disabled provider to exchange tokens. However, existing tokens still grant access.

`attribute_mapping`

`map<string, string>`

Maps attributes from authentication credentials issued by an external identity provider to Google Cloud attributes, such as `subject` and `segment` .

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

[A Common Expression Language](https://opensource.google/projects/cel) expression, in plain text, to restrict what otherwise valid authentication credentials issued by the provider should not be accepted.

The expression must output a boolean representing whether to allow the federation.

The following keywords may be referenced in the expressions:

  - `assertion` : JSON representing the authentication credential issued by the provider.
  - `google` : The Google attributes mapped from the assertion in the `attribute_mappings` .
  - `attribute` : The custom attributes mapped from the assertion in the `attribute_mappings` .

The maximum length of the condition expression is 4096 characters. If unspecified, all valid authentication credentials are accepted.

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

Required. The OIDC issuer URL. Must be an HTTPS endpoint.

`allowed_audiences[]`

`string`

Acceptable values for the `aud` field (audience) in the OIDC token. Token exchange requests are rejected if the token audience does not match one of the configured values. Each audience may be at most 256 characters. A maximum of 10 audiences may be configured.

If this list is empty, the OIDC token audience must be equal to the full canonical resource name of the WorkloadIdentityPoolProvider, with or without the HTTPS prefix. For example:

    //iam.googleapis.com/projects/<project-number>/locations/<location>/workloadIdentityPools/<pool-id>/providers/<provider-id>
    https://iam.googleapis.com/projects/<project-number>/locations/<location>/workloadIdentityPools/<pool-id>/providers/<provider-id>

`jwks_json`

`string`

Optional. OIDC JWKs in JSON String format. For details on definition of a JWK, see <https://tools.ietf.org/html/rfc7517> . If not set, then we use the `jwks_uri` from the discovery document fetched from the .well-known path for the `issuer_uri` . Currently, RSA and EC asymmetric keys are supported. The JWK must use following format and include only the following fields: { "keys": \[ { "kty": "RSA/EC", "alg": " ", "use": "sig", "kid": " ", "n": "", "e": "", "x": "", "y": "", "crv": "" } \] }

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

## WorkloadIdentityPoolProviderOperationMetadata

This type has no fields.

Metadata for long-running WorkloadIdentityPoolProvider operations.
