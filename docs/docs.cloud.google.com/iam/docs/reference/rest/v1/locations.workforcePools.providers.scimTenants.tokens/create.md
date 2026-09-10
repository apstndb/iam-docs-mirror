---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/create
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/create
title: 'Method: locations.workforcePools.providers.scimTenants.tokens.create'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/create#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/create#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/create#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/create#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/create#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/create#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/create#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/create#try-it)

Gemini Enterprise only. Creates a new `  WorkforcePoolProviderScimToken  ` in a `  WorkforcePoolProviderScimTenant  ` . You cannot reuse the name of a deleted SCIM token until 30 days after deletion.

### HTTP request

`POST https://iam.googleapis.com/v1/{parent=locations/*/workforcePools/*/providers/*/scimTenants/*}/tokens`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. Gemini Enterprise only. The parent tenant to create SCIM token. Format: 'locations/{location}/workforcePools/{workforcePool}/providers/{provider}/scimTenants/{scim\_tenant}'

### Query parameters

Parameters

`workforcePoolProviderScimTokenId`

`string`

Required. Gemini Enterprise only. The ID to use for the SCIM token, which becomes the final component of the resource name. This value should be 4-32 characters and follow the pattern: `([a-z]([a-z0-9\\-]{2,30}[a-z0-9]))`

### Request body

The request body contains an instance of `  WorkforcePoolProviderScimToken  ` .

### Response body

If successful, the response body contains a newly created instance of `  WorkforcePoolProviderScimToken  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
