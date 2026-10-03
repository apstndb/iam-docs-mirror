---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/testIamPermissions
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/testIamPermissions
title: 'Method: projects.serviceAccounts.testIamPermissions'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/testIamPermissions#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/testIamPermissions#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/testIamPermissions#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/testIamPermissions#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/testIamPermissions#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/testIamPermissions#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/testIamPermissions#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/testIamPermissions#try-it)

Tests whether the caller has the specified permissions on a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .

### HTTP request

`POST https://iam.googleapis.com/v1/{resource=projects/*/serviceAccounts/*}:testIamPermissions`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                                                                                                                                                     |
|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resource` | `string` REQUIRED: The resource for which the policy detail is being requested. See [Resource names](https://cloud.google.com/apis/design/resource_names) for the appropriate value for this field. |

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "permissions": [
    string
  ]
}
```

| Fields          |                                                                                                                                                                                                                                           |
|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `permissions[]` | `string` The set of permissions to check for the `resource` . Permissions with wildcards (such as `*` or `storage.*` ) are not allowed. For more information see [IAM Overview](https://cloud.google.com/iam/docs/overview#permissions) . |

### Response body

If successful, the response body contains an instance of [`TestIamPermissionsResponse`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TestIamPermissionsResponse) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
