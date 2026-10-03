---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/ListAccessPoliciesResponse
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/ListAccessPoliciesResponse
title: ListAccessPoliciesResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/ListAccessPoliciesResponse#SCHEMA_REPRESENTATION)

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

| Fields             |                                                                                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `accessPolicies[]` | `object ( `[`AccessPolicy`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy)` )` The access policies from the specified parent. |
| `nextPageToken`    | `string` Optional. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.                                           |
