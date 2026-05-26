---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/list
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/list
title: 'Method: organizations.locations.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/list#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/list#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/list#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/list#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/list#try-it)

Lists information about the supported locations for this service. This method can be called in two ways:

  - **List all public locations:** Use the path `GET /v1/locations` .
  - **List project-visible locations:** Use the path `GET /v1/projects/{projectId}/locations` . This may include public locations as well as private or other locations specifically visible to the project.

### HTTP request

`GET https://privilegedaccessmanager.googleapis.com/v1beta/{name=organizations/*}/locations`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

The resource that owns the locations collection, if applicable.

### Query parameters

Parameters

`filter`

`string`

A filter to narrow down results to a preferred subset. The filtering language accepts strings like `"displayName=tokyo"` , and is documented in more detail in [AIP-160](https://google.aip.dev/160) .

`pageSize`

`integer`

The maximum number of results to return. If not set, the service selects a default.

`pageToken`

`string`

A page token received from the `nextPageToken` field in the response. Send that page token to receive the subsequent page.

`extraLocationTypes[]`

`string`

Optional. Do not use this field. It is unsupported and is ignored unless explicitly documented otherwise. This is primarily for internal usage.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  ListLocationsResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `privilegedaccessmanager.locations.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
