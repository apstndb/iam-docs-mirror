---
name: documents/docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/revoke
uri: https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/revoke
title: 'Method: organizations.revoke'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/revoke#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/revoke#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/revoke#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/revoke#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/revoke#body.response_body)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/revoke#try-it)

Revokes a given token by following [OAuth 2.0 Token Revocation](https://tools.ietf.org/html/rfc7009) . This method invalidates the provided token, preventing its future use. This API only revokes refresh tokens issued for workforce pools.

### HTTP request

`POST https://cloudoauth.googleapis.com/v1/{parent=organizations/*}/revoke`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                                                                                                                                          |
|------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`   | `string` Optional. The resource name of the parent organization. Format: `organizations/{organization_id}` . This field is populated only for tenant-specific token revocation requests. |

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "token": string,
  "tokenTypeHint": string
}
```

| Fields          |                                                                                               |
|-----------------|-----------------------------------------------------------------------------------------------|
| `token`         | `string` Required. The OAuth 2.0 security token to revoke. Only refresh tokens are supported. |
| `tokenTypeHint` | `string` Optional. The type of the given token. The only supported value is `refresh_token` . |

### Response body

If successful, the response body is empty.
