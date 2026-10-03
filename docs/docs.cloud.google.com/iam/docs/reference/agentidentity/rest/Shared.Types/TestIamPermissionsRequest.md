---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/Shared.Types/TestIamPermissionsRequest
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/Shared.Types/TestIamPermissionsRequest
title: TestIamPermissionsRequest
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/Shared.Types/TestIamPermissionsRequest#SCHEMA_REPRESENTATION)

Request message for `authProviders.testIamPermissions` method.

**JSON representation**

```
{
  "resource": string,
  "permissions": [
    string
  ]
}
```

| Fields          |                                                                                                                                                                                                                                           |
|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resource`      | `string` REQUIRED: The resource for which the policy detail is being requested. See [Resource names](https://cloud.google.com/apis/design/resource_names) for the appropriate value for this field.                                       |
| `permissions[]` | `string` The set of permissions to check for the `resource` . Permissions with wildcards (such as `*` or `storage.*` ) are not allowed. For more information see [IAM Overview](https://cloud.google.com/iam/docs/overview#permissions) . |
