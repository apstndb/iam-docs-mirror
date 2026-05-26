---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers/delete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers/delete
title: 'Method: projects.locations.workloadIdentityPools.providers.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers/delete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers/delete#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers/delete#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers/delete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers/delete#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers/delete#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers/delete#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers/delete#try-it)

Deletes a `  WorkloadIdentityPoolProvider  ` . Deleting a provider does not revoke credentials that have already been issued; they continue to grant access. You can undelete a provider for 30 days. After 30 days, deletion is permanent. You cannot update deleted providers. However, you can view and list them.

### HTTP request

`DELETE https://iam.googleapis.com/v1beta/{name=projects/*/locations/*/workloadIdentityPools/*/providers/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The name of the provider to delete.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `iam.workloadIdentityPoolProviders.delete`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
