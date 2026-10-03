---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1/SearchEntitlementsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/SearchEntitlementsResponse
title: SearchEntitlementsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/SearchEntitlementsResponse#SCHEMA_REPRESENTATION)

Response message for `SearchEntitlements` method.

**JSON representation**

```
{
  "entitlements": [
    {
      object (Entitlement)
    }
  ],
  "nextPageToken": string
}
```

| Fields           |                                                                                                                                                                   |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `entitlements[]` | `object ( `[`Entitlement`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements#Entitlement)` )` The list of entitlements. |
| `nextPageToken`  | `string` A token identifying a page of results the server should return.                                                                                          |
