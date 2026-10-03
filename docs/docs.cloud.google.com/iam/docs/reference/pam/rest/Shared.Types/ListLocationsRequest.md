---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/Shared.Types/ListLocationsRequest
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/Shared.Types/ListLocationsRequest
title: ListLocationsRequest
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/Shared.Types/ListLocationsRequest#SCHEMA_REPRESENTATION)

The request message for `Locations.ListLocations` .

**JSON representation**

```
{
  "name": string,
  "filter": string,
  "pageSize": integer,
  "pageToken": string,
  "extraLocationTypes": [
    string
  ]
}
```

| Fields                 |                                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`                 | `string` The resource that owns the locations collection, if applicable.                                                                                                                                        |
| `filter`               | `string` A filter to narrow down results to a preferred subset. The filtering language accepts strings like `"displayName=tokyo"` , and is documented in more detail in [AIP-160](https://google.aip.dev/160) . |
| `pageSize`             | `integer` The maximum number of results to return. If not set, the service selects a default.                                                                                                                   |
| `pageToken`            | `string` A page token received from the `nextPageToken` field in the response. Send that page token to receive the subsequent page.                                                                             |
| `extraLocationTypes[]` | `string` Optional. Do not use this field. It is unsupported and is ignored unless explicitly documented otherwise. This is primarily for internal usage.                                                        |
