---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/SearchGrantsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/SearchGrantsResponse
title: SearchGrantsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/SearchGrantsResponse#SCHEMA_REPRESENTATION)

Response message for `SearchGrants` method.

**JSON representation**

```
{
  "grants": [
    {
      object (Grant)
    }
  ],
  "nextPageToken": string
}
```

| Fields          |                                                                                                                                                            |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `grants[]`      | `object ( `[`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants#Grant)` )` The list of grants. |
| `nextPageToken` | `string` A token identifying a page of results the server should return.                                                                                   |
