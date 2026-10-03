---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/ListGrantsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/ListGrantsResponse
title: ListGrantsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/ListGrantsResponse#SCHEMA_REPRESENTATION)

Message for response to listing grants.

**JSON representation**

```
{
  "grants": [
    {
      object (Grant)
    }
  ],
  "nextPageToken": string,
  "unreachable": [
    string
  ]
}
```

| Fields          |                                                                                                                                                            |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `grants[]`      | `object ( `[`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants#Grant)` )` The list of grants. |
| `nextPageToken` | `string` A token identifying a page of results the server should return.                                                                                   |
| `unreachable[]` | `string` Locations that could not be reached.                                                                                                              |
