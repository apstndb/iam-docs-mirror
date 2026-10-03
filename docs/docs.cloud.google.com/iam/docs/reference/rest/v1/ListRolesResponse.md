---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/ListRolesResponse
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/ListRolesResponse
title: ListRolesResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/ListRolesResponse#SCHEMA_REPRESENTATION)

The response containing the roles defined under a resource.

**JSON representation**

```
{
  "roles": [
    {
      object (Role)
    }
  ],
  "nextPageToken": string
}
```

| Fields          |                                                                                                                                                |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| `roles[]`       | `object ( `[`Role`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role)` )` The Roles defined on this resource. |
| `nextPageToken` | `string` To retrieve the next page of results, set `ListRolesRequest.page_token` to this value.                                                |
