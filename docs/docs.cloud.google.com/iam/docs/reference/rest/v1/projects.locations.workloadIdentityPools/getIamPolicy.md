---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/getIamPolicy
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/getIamPolicy
title: 'Method: projects.locations.workloadIdentityPools.getIamPolicy'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/getIamPolicy#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/getIamPolicy#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/getIamPolicy#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/getIamPolicy#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/getIamPolicy#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/getIamPolicy#body.aspect)
- [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/getIamPolicy#body.aspect_1)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/getIamPolicy#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/getIamPolicy#try-it)

Gets the IAM policy of a [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools#WorkloadIdentityPool) .

### HTTP request

`POST https://iam.googleapis.com/v1/{resource=projects/*/locations/*/workloadIdentityPools/*}:getIamPolicy`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                                                                                                                                              |
|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resource` | `string` REQUIRED: The resource for which the policy is being requested. See [Resource names](https://cloud.google.com/apis/design/resource_names) for the appropriate value for this field. |

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "options": {
    object (GetPolicyOptions)
  }
}
```

| Fields    |                                                                                                                                                                                                                       |
|-----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `options` | `object ( `[`GetPolicyOptions`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/GetPolicyOptions)` )` OPTIONAL: A `GetPolicyOptions` object for specifying options to `workloadIdentityPools.getIamPolicy` . |

### Response body

If successful, the response body contains an instance of [`Policy`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/Policy) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `resource` resource:

- `CALLBACK`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
