---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/list
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/list
title: 'Method: projects.locations.oauthClients.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/list#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/list#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/list#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/list#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/list#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/list#body.ListOauthClientsResponse.SCHEMA_REPRESENTATION)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/list#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/list#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/list#try-it)

Lists all non-deleted [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) s in a project. If `showDeleted` is set to `true` , then deleted [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) s are also listed.

### HTTP request

`GET https://iam.googleapis.com/v1/{parent=projects/*/locations/*}/oauthClients`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                                                                                                                    |
|------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`   | `string` Required. The parent to list [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) s for. |

### Query parameters

| Parameters    |                                                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `pageSize`    | `integer` Optional. The maximum number of [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) s to return. If unspecified, at most 50 [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) s will be returned. The maximum value is 100; values above 100 are truncated to 100. |
| `pageToken`   | `string` Optional. A page token, received from a previous `oauthClients.list` call. Provide this to retrieve the subsequent page.                                                                                                                                                                                                                                                                                  |
| `showDeleted` | `boolean` Optional. Whether to return soft-deleted [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) s.                                                                                                                                                                                                                                        |

### Request body

The request body must be empty.

### Response body

Response message for oauthClients.list.

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "oauthClients": [
    {
      object (OauthClient)
    }
  ],
  "nextPageToken": string
}
```

| Fields           |                                                                                                                                                                                                                                                                         |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `oauthClients[]` | `object ( `[`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient)` )` A list of [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) s. |
| `nextPageToken`  | `string` Optional. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.                                                                                                                        |

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
