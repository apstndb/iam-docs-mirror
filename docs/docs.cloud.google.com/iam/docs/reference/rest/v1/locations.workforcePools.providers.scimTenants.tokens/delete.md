---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/delete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/delete
title: 'Method: locations.workforcePools.providers.scimTenants.tokens.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/delete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/delete#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/delete#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/delete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/delete#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/delete#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/delete#try-it)

Gemini Enterprise only. Deletes a `  WorkforcePoolProviderScimToken  ` . You can undelete a SCIM token for 30 days. After 30 days, the SCIM token is permanently deleted. You cannot update deleted SCIM tokens, however, you can view and list them.

### HTTP request

`DELETE https://iam.googleapis.com/v1/{name=locations/*/workforcePools/*/providers/*/scimTenants/*/tokens/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. Gemini Enterprise only. The name of the SCIM token to delete.

Format: `locations/{location}/workforcePools/{workforcePool}/providers/{provider}/scimTenants/{scim_tenant}/tokens/{token}`

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  WorkforcePoolProviderScimToken  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
