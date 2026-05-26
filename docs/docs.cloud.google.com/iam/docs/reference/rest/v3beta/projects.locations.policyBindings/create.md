---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings/create
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings/create
title: 'Method: projects.locations.policyBindings.create'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings/create#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings/create#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings/create#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings/create#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings/create#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings/create#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings/create#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings/create#try-it)

Creates a policy binding and returns a long-running operation. Callers will need the IAM permissions on both the policy and target. After the binding is created, the policy is applied to the target.

### HTTP request

`POST https://iam.googleapis.com/v3beta/{parent=projects/*/locations/*}/policyBindings`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource where this policy binding will be created. The binding parent is the closest Resource Manager resource (project, folder or organization) to the binding target.

Format:

  - `projects/{projectId}/locations/{location}`
  - `projects/{projectNumber}/locations/{location}`
  - `folders/{folderId}/locations/{location}`
  - `organizations/{organizationId}/locations/{location}`

### Query parameters

Parameters

`policyBindingId`

`string`

Required. The ID to use for the policy binding, which will become the final component of the policy binding's resource name.

This value must start with a lowercase letter followed by up to 62 lowercase letters, numbers, hyphens, or dots. Pattern, /\[a-z\]\[a-z0-9-.\]{2,62}/.

`validateOnly`

`boolean`

Optional. If set, validate the request and preview the creation, but do not actually post it.

### Request body

The request body contains an instance of `  PolicyBinding  ` .

### Response body

If successful, the response body contains a newly created instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
