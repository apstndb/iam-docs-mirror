---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/list
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/list
title: 'Method: organizations.locations.entitlements.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/list#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/list#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/list#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/list#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/list#try-it)

Lists the entitlements in a given project, folder, organization, and in a given location.

### HTTP request

`GET https://privilegedaccessmanager.googleapis.com/v1/{parent=organizations/*/locations/*}/entitlements`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent which owns the entitlement resources.

### Query parameters

Parameters

`pageSize`

`integer`

Optional. Requested page size. Server may return fewer items than requested. If unspecified, the server picks an appropriate default.

`pageToken`

`string`

Optional. A token identifying a page of results the server should return.

`filter`

`string`

Optional. Filtering results.

`orderBy`

`string`

Optional. Hint for how to order the results.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  ListEntitlementsResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `privilegedaccessmanager.entitlements.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
