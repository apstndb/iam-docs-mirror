---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/Shared.Types/TestIamPermissionsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/Shared.Types/TestIamPermissionsResponse
title: TestIamPermissionsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/Shared.Types/TestIamPermissionsResponse#SCHEMA_REPRESENTATION)

Response message for `authProviders.testIamPermissions` method.

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
