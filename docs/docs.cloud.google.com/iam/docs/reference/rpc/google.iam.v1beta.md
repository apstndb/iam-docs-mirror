---
name: documents/docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta
uri: https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta
title: Package google.iam.v1beta
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

- [`WorkloadIdentityPools`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPools) (interface)
- [`CreateWorkloadIdentityPoolProviderRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.CreateWorkloadIdentityPoolProviderRequest) (message)
- [`CreateWorkloadIdentityPoolRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.CreateWorkloadIdentityPoolRequest) (message)
- [`DeleteWorkloadIdentityPoolProviderRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.DeleteWorkloadIdentityPoolProviderRequest) (message)
- [`DeleteWorkloadIdentityPoolRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.DeleteWorkloadIdentityPoolRequest) (message)
- [`GetWorkloadIdentityPoolProviderRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.GetWorkloadIdentityPoolProviderRequest) (message)
- [`GetWorkloadIdentityPoolRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.GetWorkloadIdentityPoolRequest) (message)
- [`ListWorkloadIdentityPoolProvidersRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.ListWorkloadIdentityPoolProvidersRequest) (message)
- [`ListWorkloadIdentityPoolProvidersResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.ListWorkloadIdentityPoolProvidersResponse) (message)
- [`ListWorkloadIdentityPoolsRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.ListWorkloadIdentityPoolsRequest) (message)
- [`ListWorkloadIdentityPoolsResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.ListWorkloadIdentityPoolsResponse) (message)
- [`UndeleteWorkloadIdentityPoolProviderRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.UndeleteWorkloadIdentityPoolProviderRequest) (message)
- [`UndeleteWorkloadIdentityPoolRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.UndeleteWorkloadIdentityPoolRequest) (message)
- [`UpdateWorkloadIdentityPoolProviderRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.UpdateWorkloadIdentityPoolProviderRequest) (message)
- [`UpdateWorkloadIdentityPoolRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.UpdateWorkloadIdentityPoolRequest) (message)
- [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool) (message)
- [`WorkloadIdentityPool.State`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool.State) (enum)
- [`WorkloadIdentityPoolOperationMetadata`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolOperationMetadata) (message)
- [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider) (message)
- [`WorkloadIdentityPoolProvider.Aws`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider.Aws) (message)
- [`WorkloadIdentityPoolProvider.Oidc`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider.Oidc) (message)
- [`WorkloadIdentityPoolProvider.State`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider.State) (enum)
- [`WorkloadIdentityPoolProviderOperationMetadata`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProviderOperationMetadata) (message)

## WorkloadIdentityPools

Manages WorkloadIdentityPools.

**CreateWorkloadIdentityPool**

`rpc CreateWorkloadIdentityPool( `[`CreateWorkloadIdentityPoolRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.CreateWorkloadIdentityPoolRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Creates a new [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool) .

You cannot reuse the name of a deleted pool until 30 days after deletion.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `iam.workloadIdentityPools.create`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**CreateWorkloadIdentityPoolProvider**

`rpc CreateWorkloadIdentityPoolProvider( `[`CreateWorkloadIdentityPoolProviderRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.CreateWorkloadIdentityPoolProviderRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Creates a new [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider) in a [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool) .

You cannot reuse the name of a deleted provider until 30 days after deletion.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `iam.workloadIdentityPoolProviders.create`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**DeleteWorkloadIdentityPool**

`rpc DeleteWorkloadIdentityPool( `[`DeleteWorkloadIdentityPoolRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.DeleteWorkloadIdentityPoolRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Deletes a [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool) .

You cannot use a deleted pool to exchange external credentials for Google Cloud credentials. However, deletion does not revoke credentials that have already been issued. Credentials issued for a deleted pool do not grant access to resources. If the pool is undeleted, and the credentials are not expired, they grant access again. You can undelete a pool for 30 days. After 30 days, deletion is permanent. You cannot update deleted pools. However, you can view and list them.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.workloadIdentityPools.delete`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**DeleteWorkloadIdentityPoolProvider**

`rpc DeleteWorkloadIdentityPoolProvider( `[`DeleteWorkloadIdentityPoolProviderRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.DeleteWorkloadIdentityPoolProviderRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Deletes a [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider) . Deleting a provider does not revoke credentials that have already been issued; they continue to grant access. You can undelete a provider for 30 days. After 30 days, deletion is permanent. You cannot update deleted providers. However, you can view and list them.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.workloadIdentityPoolProviders.delete`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**GetWorkloadIdentityPool**

`rpc GetWorkloadIdentityPool( `[`GetWorkloadIdentityPoolRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.GetWorkloadIdentityPoolRequest)` ) returns ( `[`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool)` )`

Gets an individual [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool) .

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.workloadIdentityPools.get`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**GetWorkloadIdentityPoolProvider**

`rpc GetWorkloadIdentityPoolProvider( `[`GetWorkloadIdentityPoolProviderRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.GetWorkloadIdentityPoolProviderRequest)` ) returns ( `[`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider)` )`

Gets an individual [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider) .

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.workloadIdentityPoolProviders.get`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**ListWorkloadIdentityPoolProviders**

`rpc ListWorkloadIdentityPoolProviders( `[`ListWorkloadIdentityPoolProvidersRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.ListWorkloadIdentityPoolProvidersRequest)` ) returns ( `[`ListWorkloadIdentityPoolProvidersResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.ListWorkloadIdentityPoolProvidersResponse)` )`

Lists all non-deleted [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider) s in a [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool) . If `show_deleted` is set to `true` , then deleted providers are also listed.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `iam.workloadIdentityPoolProviders.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**ListWorkloadIdentityPools**

`rpc ListWorkloadIdentityPools( `[`ListWorkloadIdentityPoolsRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.ListWorkloadIdentityPoolsRequest)` ) returns ( `[`ListWorkloadIdentityPoolsResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.ListWorkloadIdentityPoolsResponse)` )`

Lists all non-deleted [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool) s in a project. If `show_deleted` is set to `true` , then deleted pools are also listed.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `iam.workloadIdentityPools.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**UndeleteWorkloadIdentityPool**

`rpc UndeleteWorkloadIdentityPool( `[`UndeleteWorkloadIdentityPoolRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.UndeleteWorkloadIdentityPoolRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Undeletes a [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool) , as long as it was deleted fewer than 30 days ago.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.workloadIdentityPools.undelete`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**UndeleteWorkloadIdentityPoolProvider**

`rpc UndeleteWorkloadIdentityPoolProvider( `[`UndeleteWorkloadIdentityPoolProviderRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.UndeleteWorkloadIdentityPoolProviderRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Undeletes a [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider) , as long as it was deleted fewer than 30 days ago.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.workloadIdentityPoolProviders.undelete`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**UpdateWorkloadIdentityPool**

`rpc UpdateWorkloadIdentityPool( `[`UpdateWorkloadIdentityPoolRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.UpdateWorkloadIdentityPoolRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Updates an existing [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool) .

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.workloadIdentityPools.update`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**UpdateWorkloadIdentityPoolProvider**

`rpc UpdateWorkloadIdentityPoolProvider( `[`UpdateWorkloadIdentityPoolProviderRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.UpdateWorkloadIdentityPoolProviderRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Updates an existing [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider) .

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.workloadIdentityPoolProviders.update`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

## CreateWorkloadIdentityPoolProviderRequest

Request message for CreateWorkloadIdentityPoolProvider.

| Fields                               |                                                                                                                                                                                                                                                                |
|--------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`                             | `string` Required. The pool to create this provider in.                                                                                                                                                                                                        |
| `workload_identity_pool_provider`    | [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider) Required. The provider to create.                                                                      |
| `workload_identity_pool_provider_id` | `string` Required. The ID for the provider, which becomes the final component of the resource name. This value must be 4-32 characters, and may contain the characters \[a-z0-9-\]. The prefix `gcp-` is reserved for use by Google, and may not be specified. |

## CreateWorkloadIdentityPoolRequest

Request message for CreateWorkloadIdentityPool.

| Fields                      |                                                                                                                                                                                                                                                                     |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`                    | `string` Required. The parent resource to create the pool in. The only supported location is `global` .                                                                                                                                                             |
| `workload_identity_pool`    | [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool) Required. The pool to create.                                                                                               |
| `workload_identity_pool_id` | `string` Required. The ID to use for the pool, which becomes the final component of the resource name. This value should be 4-32 characters, and may contain the characters \[a-z0-9-\]. The prefix `gcp-` is reserved for use by Google, and may not be specified. |

## DeleteWorkloadIdentityPoolProviderRequest

Request message for DeleteWorkloadIdentityPoolProvider.

| Fields |                                                        |
|--------|--------------------------------------------------------|
| `name` | `string` Required. The name of the provider to delete. |

## DeleteWorkloadIdentityPoolRequest

Request message for DeleteWorkloadIdentityPool.

| Fields |                                                    |
|--------|----------------------------------------------------|
| `name` | `string` Required. The name of the pool to delete. |

## GetWorkloadIdentityPoolProviderRequest

Request message for GetWorkloadIdentityPoolProvider.

| Fields |                                                          |
|--------|----------------------------------------------------------|
| `name` | `string` Required. The name of the provider to retrieve. |

## GetWorkloadIdentityPoolRequest

Request message for GetWorkloadIdentityPool.

| Fields |                                                      |
|--------|------------------------------------------------------|
| `name` | `string` Required. The name of the pool to retrieve. |

## ListWorkloadIdentityPoolProvidersRequest

Request message for ListWorkloadIdentityPoolProviders.

| Fields         |                                                                                                                                                                        |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`       | `string` Required. The pool to list providers for.                                                                                                                     |
| `page_size`    | `int32` The maximum number of providers to return. If unspecified, at most 50 providers are returned. The maximum value is 100; values above 100 are truncated to 100. |
| `page_token`   | `string` A page token, received from a previous `ListWorkloadIdentityPoolProviders` call. Provide this to retrieve the subsequent page.                                |
| `show_deleted` | `bool` Whether to return soft-deleted providers.                                                                                                                       |

## ListWorkloadIdentityPoolProvidersResponse

Response message for ListWorkloadIdentityPoolProviders.

| Fields                               |                                                                                                                                                                              |
|--------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `workload_identity_pool_providers[]` | [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider) A list of providers. |
| `next_page_token`                    | `string` A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.                                      |

## ListWorkloadIdentityPoolsRequest

Request message for ListWorkloadIdentityPools.

| Fields         |                                                                                                                                                                   |
|----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`       | `string` Required. The parent resource to list pools for.                                                                                                         |
| `page_size`    | `int32` The maximum number of pools to return. If unspecified, at most 50 pools are returned. The maximum value is 1000; values above are 1000 truncated to 1000. |
| `page_token`   | `string` A page token, received from a previous `ListWorkloadIdentityPools` call. Provide this to retrieve the subsequent page.                                   |
| `show_deleted` | `bool` Whether to return soft-deleted pools.                                                                                                                      |

## ListWorkloadIdentityPoolsResponse

Response message for ListWorkloadIdentityPools.

| Fields                      |                                                                                                                                                          |
|-----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| `workload_identity_pools[]` | [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool) A list of pools. |
| `next_page_token`           | `string` A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.                  |

## UndeleteWorkloadIdentityPoolProviderRequest

Request message for UndeleteWorkloadIdentityPoolProvider.

| Fields |                                                          |
|--------|----------------------------------------------------------|
| `name` | `string` Required. The name of the provider to undelete. |

## UndeleteWorkloadIdentityPoolRequest

Request message for UndeleteWorkloadIdentityPool.

| Fields |                                                      |
|--------|------------------------------------------------------|
| `name` | `string` Required. The name of the pool to undelete. |

## UpdateWorkloadIdentityPoolProviderRequest

Request message for UpdateWorkloadIdentityPoolProvider.

| Fields                            |                                                                                                                                                                                           |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `workload_identity_pool_provider` | [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider) Required. The provider to update. |
| `update_mask`                     | [`FieldMask`](https://protobuf.dev/reference/protobuf/google.protobuf/#field-mask) Required. The list of fields to update.                                                                |

## UpdateWorkloadIdentityPoolRequest

Request message for UpdateWorkloadIdentityPool.

| Fields                   |                                                                                                                                                                                                                      |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `workload_identity_pool` | [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool) Required. The pool to update. The `name` field is used to identify the pool. |
| `update_mask`            | [`FieldMask`](https://protobuf.dev/reference/protobuf/google.protobuf/#field-mask) Required. The list of fields to update.                                                                                           |

## WorkloadIdentityPool

Represents a collection of external workload identities. You can define IAM policies to grant these identities access to Google Cloud resources.

| Fields         |                                                                                                                                                                                                    |
|----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`         | `string` Output only. The resource name of the pool.                                                                                                                                               |
| `display_name` | `string` A display name for the pool. Cannot exceed 32 characters.                                                                                                                                 |
| `description`  | `string` A description of the pool. Cannot exceed 256 characters.                                                                                                                                  |
| `state`        | [`State`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPool.State) Output only. The state of the pool.                                 |
| `disabled`     | `bool` Whether the pool is disabled. You cannot use a disabled pool to exchange tokens, or use existing tokens to access resources. If the pool is re-enabled, existing tokens grant access again. |
| `expire_time`  | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. Time after which the workload identity pool will be permanently purged and cannot be recovered.     |

## State

The current state of the pool.

| Enums               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|---------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `STATE_UNSPECIFIED` | State unspecified.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| `ACTIVE`            | The pool is active, and may be used in Google Cloud policies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `DELETED`           | The pool is soft-deleted. Soft-deleted pools are permanently deleted after approximately 30 days. You can restore a soft-deleted pool using [`UndeleteWorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPools.UndeleteWorkloadIdentityPool) . You cannot reuse the ID of a soft-deleted pool until it is permanently deleted. While a pool is deleted, you cannot use it to exchange tokens, or use existing tokens to access resources. If the pool is undeleted, existing tokens grant access again. |

## WorkloadIdentityPoolOperationMetadata

This type has no fields.

Metadata for long-running WorkloadIdentityPool operations.

## WorkloadIdentityPoolProvider

A configuration for an external identity provider.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>Output only. The resource name of the provider.</p></td>
</tr>
<tr class="even">
<td><code>display_name</code></td>
<td><p><code>string</code></p>
<p>A display name for the provider. Cannot exceed 32 characters.</p></td>
</tr>
<tr class="odd">
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>A description for the provider. Cannot exceed 256 characters.</p></td>
</tr>
<tr class="even">
<td><code>state</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider.State"><code>State</code></a></p>
<p>Output only. The state of the provider.</p></td>
</tr>
<tr class="odd">
<td><code>disabled</code></td>
<td><p><code>bool</code></p>
<p>Whether the provider is disabled. You cannot use a disabled provider to exchange tokens. However, existing tokens still grant access.</p></td>
</tr>
<tr class="even">
<td><code>attribute_mapping</code></td>
<td><p><code>map&lt;string, string&gt;</code></p>
<p>Maps attributes from authentication credentials issued by an external identity provider to Google Cloud attributes, such as <code>subject</code> and <code>segment</code> .</p>
<p>Each key must be a string specifying the Google Cloud IAM attribute to map to.</p>
<p>The following keys are supported:</p>
<ul>
<li><p><code>google.subject</code> : The principal IAM is authenticating. You can reference this value in IAM bindings. This is also the subject that appears in Cloud Logging logs. Cannot exceed 127 bytes.</p></li>
<li><p><code>google.groups</code> : Groups the external identity belongs to. You can grant groups access to resources using an IAM <code>principalSet</code> binding; access applies to all members of the group.</p></li>
</ul>
<p>You can also provide custom attributes by specifying <code>attribute.{custom_attribute}</code> , where <code>{custom_attribute}</code> is the name of the custom attribute to be mapped. You can define a maximum of 50 custom attributes. The maximum length of a mapped attribute key is 100 characters, and the key may only contain the characters [a-z0-9_].</p>
<p>You can reference these attributes in IAM policies to define fine-grained access for a workload to Google Cloud resources. For example:</p>
<ul>
<li><p><code>google.subject</code> : <code>principal://iam.googleapis.com/projects/{project}/locations/{location}/workloadIdentityPools/{pool}/subject/{value}</code></p></li>
<li><p><code>google.groups</code> : <code>principalSet://iam.googleapis.com/projects/{project}/locations/{location}/workloadIdentityPools/{pool}/group/{value}</code></p></li>
<li><p><code>attribute.{custom_attribute}</code> : <code>principalSet://iam.googleapis.com/projects/{project}/locations/{location}/workloadIdentityPools/{pool}/attribute.{custom_attribute}/{value}</code></p></li>
</ul>
<p>Each value must be a <a href="https://opensource.google/projects/cel">Common Expression Language</a> function that maps an identity provider credential to the normalized attribute specified by the corresponding map key.</p>
<p>You can use the <code>assertion</code> keyword in the expression to access a JSON representation of the authentication credential issued by the provider.</p>
<p>The maximum length of an attribute mapping expression is 2048 characters. When evaluated, the total size of all mapped attributes must not exceed 8KB.</p>
<p>For AWS providers, if no attribute mapping is defined, the following default mapping applies:</p>
<pre data-fenced=""><code>{
  &quot;google.subject&quot;:&quot;assertion.arn&quot;,
  &quot;attribute.aws_role&quot;:
    &quot;assertion.arn.contains(&#39;assumed-role&#39;)&quot;
    &quot; ? assertion.arn.extract(&#39;{account_arn}assumed-role/&#39;)&quot;
    &quot;   + &#39;assumed-role/&#39;&quot;
    &quot;   + assertion.arn.extract(&#39;assumed-role/{role_name}/&#39;)&quot;
    &quot; : assertion.arn&quot;,
}</code></pre>
<p>If any custom attribute mappings are defined, they must include a mapping to the <code>google.subject</code> attribute.</p>
<p>For OIDC providers, you must supply a custom mapping, which must include the <code>google.subject</code> attribute. For example, the following maps the <code>sub</code> claim of the incoming credential to the <code>subject</code> attribute on a Google token:</p>
<pre data-fenced=""><code>{&quot;google.subject&quot;: &quot;assertion.sub&quot;}</code></pre></td>
</tr>
<tr class="odd">
<td><code>attribute_condition</code></td>
<td><p><code>string</code></p>
<p><a href="https://opensource.google/projects/cel">A Common Expression Language</a> expression, in plain text, to restrict what otherwise valid authentication credentials issued by the provider should not be accepted.</p>
<p>The expression must output a boolean representing whether to allow the federation.</p>
<p>The following keywords may be referenced in the expressions:</p>
<ul>
<li><code>assertion</code> : JSON representing the authentication credential issued by the provider.</li>
<li><code>google</code> : The Google attributes mapped from the assertion in the <code>attribute_mappings</code> .</li>
<li><code>attribute</code> : The custom attributes mapped from the assertion in the <code>attribute_mappings</code> .</li>
</ul>
<p>The maximum length of the <code>attribute_condition</code> expression is 4,096 characters. If unspecified, all valid authentication credentials are accepted. However, multi-tenant identity providers (such as GitHub or Terraform Cloud) require an <code>attribute_condition</code> to prevent token spoofing.</p>
<p>The following example shows how to only allow credentials with a mapped <code>google.groups</code> value of <code>admins</code> :</p>
<pre data-fenced=""><code>&quot;&#39;admins&#39; in google.groups&quot;</code></pre></td>
</tr>
<tr class="even">
<td><code>expire_time</code></td>
<td><p><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a></p>
<p>Output only. Time after which the workload identity pool provider will be permanently purged and cannot be recovered.</p></td>
</tr>
<tr class="odd">
<td>Union field <code>provider_config</code> . Identity provider configuration types. <code>provider_config</code> can be only one of the following:</td>
<td></td>
</tr>
<tr class="even">
<td><code>aws</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider.Aws"><code>Aws</code></a></p>
<p>An Amazon Web Services identity provider.</p></td>
</tr>
<tr class="odd">
<td><code>oidc</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPoolProvider.Oidc"><code>Oidc</code></a></p>
<p>An OpenId Connect 1.0 identity provider.</p></td>
</tr>
</tbody>
</table>

## Aws

Represents an Amazon Web Services identity provider.

| Fields       |                                        |
|--------------|----------------------------------------|
| `account_id` | `string` Required. The AWS account ID. |

## Oidc

Represents an OpenId Connect 1.0 identity provider.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>issuer_uri</code></td>
<td><p><code>string</code></p>
<p>Required. The OIDC issuer URL. Must be an HTTPS endpoint.</p></td>
</tr>
<tr class="even">
<td><code>allowed_audiences[]</code></td>
<td><p><code>string</code></p>
<p>Acceptable values for the <code>aud</code> field (audience) in the OIDC token. Token exchange requests are rejected if the token audience does not match one of the configured values. Each audience may be at most 256 characters. A maximum of 10 audiences may be configured.</p>
<p>If this list is empty, the OIDC token audience must be equal to the full canonical resource name of the WorkloadIdentityPoolProvider, with or without the HTTPS prefix. For example:</p>
<pre data-fenced=""><code>//iam.googleapis.com/projects/&lt;project-number&gt;/locations/&lt;location&gt;/workloadIdentityPools/&lt;pool-id&gt;/providers/&lt;provider-id&gt;
https://iam.googleapis.com/projects/&lt;project-number&gt;/locations/&lt;location&gt;/workloadIdentityPools/&lt;pool-id&gt;/providers/&lt;provider-id&gt;</code></pre></td>
</tr>
<tr class="odd">
<td><code>jwks_json</code></td>
<td><p><code>string</code></p>
<p>Optional. OIDC JWKs in JSON String format. For details on definition of a JWK, see <a href="https://tools.ietf.org/html/rfc7517">https://tools.ietf.org/html/rfc7517</a> . If not set, then we use the <code>jwks_uri</code> from the discovery document fetched from the .well-known path for the <code>issuer_uri</code> . Currently, RSA and EC asymmetric keys are supported. The JWK must use following format and include only the following fields: { "keys": [ { "kty": "RSA/EC", "alg": " ", "use": "sig", "kid": " ", "n": "", "e": "", "x": "", "y": "", "crv": "" } ] }</p></td>
</tr>
</tbody>
</table>

## State

The current state of the provider.

| Enums               |                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `STATE_UNSPECIFIED` | State unspecified.                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `ACTIVE`            | The provider is active, and may be used to validate authentication credentials.                                                                                                                                                                                                                                                                                                                                                             |
| `DELETED`           | The provider is soft-deleted. Soft-deleted providers are permanently deleted after approximately 30 days. You can restore a soft-deleted provider using [`UndeleteWorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1beta#google.iam.v1beta.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolProvider) . You cannot reuse the ID of a soft-deleted provider until it is permanently deleted. |

## WorkloadIdentityPoolProviderOperationMetadata

This type has no fields.

Metadata for long-running WorkloadIdentityPoolProvider operations.
