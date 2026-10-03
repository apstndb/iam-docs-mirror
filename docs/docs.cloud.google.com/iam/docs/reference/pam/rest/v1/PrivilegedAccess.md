---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1/PrivilegedAccess
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/PrivilegedAccess
title: PrivilegedAccess
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/PrivilegedAccess#SCHEMA_REPRESENTATION)
- [GcpIamAccess](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/PrivilegedAccess#GcpIamAccess)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/PrivilegedAccess#GcpIamAccess.SCHEMA_REPRESENTATION)
- [RoleBinding](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/PrivilegedAccess#RoleBinding)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/PrivilegedAccess#RoleBinding.SCHEMA_REPRESENTATION)

Privileged access that this service can be used to gate.

**JSON representation**

```
{

  // Union field access_type can be only one of the following:
  "gcpIamAccess": {
    object (GcpIamAccess)
  }
  // End of list of possible types for union field access_type.
}
```

| Fields                                                                      |                                                                                                                                                                            |
|-----------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `access_type` . `access_type` can be only one of the following: |                                                                                                                                                                            |
| `gcpIamAccess`                                                              | `object ( `[`GcpIamAccess`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/PrivilegedAccess#GcpIamAccess)` )` Access to a Google Cloud resource through IAM. |

## GcpIamAccess

`GcpIamAccess` represents IAM based access control on a Google Cloud resource. Refer to <https://cloud.google.com/iam/docs> to understand more about IAM.

**JSON representation**

```
{
  "resourceType": string,
  "resource": string,
  "roleBindings": [
    {
      object (RoleBinding)
    }
  ]
}
```

| Fields           |                                                                                                                                                                                         |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resourceType`   | `string` Required. The type of this resource.                                                                                                                                           |
| `resource`       | `string` Required. Name of the resource.                                                                                                                                                |
| `roleBindings[]` | `object ( `[`RoleBinding`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/PrivilegedAccess#RoleBinding)` )` Required. Role bindings that are created on successful grant. |

## RoleBinding

IAM role bindings that are created after a successful grant.

**JSON representation**

```
{
  "role": string,
  "conditionExpression": string
}
```

| Fields                |                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|-----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `role`                | `string` Required. IAM role to be granted. <https://cloud.google.com/iam/docs/roles-overview> .                                                                                                                                                                                                                                                                                                                                    |
| `conditionExpression` | `string` Optional. The expression field of the IAM condition to be associated with the role. If specified, a user with an active grant for this entitlement is able to access the resource only if this condition evaluates to true for their request. This field uses the same CEL format as IAM and supports all attributes that IAM supports, except tags. <https://cloud.google.com/iam/docs/conditions-overview#attributes> . |
