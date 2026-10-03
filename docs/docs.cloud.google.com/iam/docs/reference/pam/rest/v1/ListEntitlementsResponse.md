---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1/ListEntitlementsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/ListEntitlementsResponse
title: ListEntitlementsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/ListEntitlementsResponse#SCHEMA_REPRESENTATION)

Message for response to listing entitlements.

**JSON representation**

```
{
  "entitlements": [
    {
      object (Entitlement)
    }
  ],
  "nextPageToken": string,
  "unreachable": [
    string
  ]
}
```

| Fields           |                                                                                                                                                                   |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `entitlements[]` | `object ( `[`Entitlement`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements#Entitlement)` )` The list of entitlements. |
| `nextPageToken`  | `string` A token identifying a page of results the server should return.                                                                                          |
| `unreachable[]`  | `string` Locations that could not be reached.                                                                                                                     |
