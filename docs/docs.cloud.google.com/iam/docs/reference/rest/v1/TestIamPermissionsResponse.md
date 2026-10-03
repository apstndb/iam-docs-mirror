---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/TestIamPermissionsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/TestIamPermissionsResponse
title: TestIamPermissionsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TestIamPermissionsResponse#SCHEMA_REPRESENTATION)

Response message for `TestIamPermissions` method.

**JSON representation**

```
{
  "permissions": [
    string
  ]
}
```

| Fields          |                                                                                       |
|-----------------|---------------------------------------------------------------------------------------|
| `permissions[]` | `string` A subset of `TestPermissionsRequest.permissions` that the caller is allowed. |
