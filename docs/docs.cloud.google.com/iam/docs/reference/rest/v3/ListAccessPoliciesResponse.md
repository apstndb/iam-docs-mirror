---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/ListAccessPoliciesResponse
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/ListAccessPoliciesResponse
title: ListAccessPoliciesResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3/ListAccessPoliciesResponse#SCHEMA_REPRESENTATION)

Response message for ListAccessPolicies method.

**JSON representation**

```
{
  "accessPolicies": [
    {
      object (AccessPolicy)
    }
  ],
  "nextPageToken": string
}
```

| Fields             |                                                                                                                                                                                                |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `accessPolicies[]` | `object ( `[`AccessPolicy`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.accessPolicies#AccessPolicy)` )` The Unified Access Policies from the specified parent. |
| `nextPageToken`    | `string` Optional. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.                                               |
