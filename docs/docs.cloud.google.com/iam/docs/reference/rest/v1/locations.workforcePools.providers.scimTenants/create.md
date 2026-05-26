---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/create
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/create
title: 'Method: locations.workforcePools.providers.scimTenants.create'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/create#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/create#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/create#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/create#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/create#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/create#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/create#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/create#try-it)

Gemini Enterprise only. Creates a new `  WorkforcePoolProviderScimTenant  ` in a `  WorkforcePoolProvider  ` . You cannot reuse the name of a deleted SCIM tenant until 30 days after deletion.

### HTTP request

`POST https://iam.googleapis.com/v1/{parent=locations/*/workforcePools/*/providers/*}/scimTenants`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. Gemini Enterprise only. The parent to create SCIM tenant. Format: 'locations/{location}/workforcePools/{workforcePool}/providers/{provider}'

### Query parameters

Parameters

`workforcePoolProviderScimTenantId`

`string`

Required. Gemini Enterprise only. The ID to use for the SCIM tenant, which becomes the final component of the resource name. This value should be 4-32 characters, containing the characters `[a-z0-9-]` .

### Request body

The request body contains an instance of `  WorkforcePoolProviderScimTenant  ` .

### Response body

If successful, the response body contains a newly created instance of `  WorkforcePoolProviderScimTenant  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
