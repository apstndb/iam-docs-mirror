---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/approve
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/approve
title: 'Method: projects.locations.entitlements.grants.approve'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/approve#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/approve#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/approve#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/approve#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/approve#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/approve#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/approve#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/approve#try-it)

`grants.approve` is used to approve a grant. This method can only be called on a grant when it's in the `APPROVAL_AWAITED` state. This operation can't be undone.

### HTTP request

`POST https://privilegedaccessmanager.googleapis.com/v1beta/{name=projects/*/locations/*/entitlements/*/grants/*}:approve`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                        |
|------------|------------------------------------------------------------------------|
| `name`     | `string` Required. Name of the grant resource which is being approved. |

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "reason": string
}
```

| Fields   |                                                                                                                                                                                    |
|----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `reason` | `string` Optional. The reason for approving this grant. This is required if the `requireApproverJustification` field of the `ManualApprovals` workflow used in this grant is true. |

### Response body

If successful, the response body contains an instance of [`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants#Grant) .

### Authorization scopes

Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
