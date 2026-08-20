---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/getIamPolicy
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/getIamPolicy
title: 'Method: projects.locations.authProviders.getIamPolicy'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/getIamPolicy#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/getIamPolicy#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/getIamPolicy#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/getIamPolicy#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/getIamPolicy#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/getIamPolicy#body.aspect)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/getIamPolicy#try-it)

Gets the access control policy for a resource. Returns an empty policy if the resource exists and does not have a policy set.

### HTTP request

`GET https://agentidentity.googleapis.com/v1/{resource=projects/*/locations/*/authProviders/*}:getIamPolicy`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`resource`

`string`

REQUIRED: The resource for which the policy is being requested. See [Resource names](https://cloud.google.com/apis/design/resource_names) for the appropriate value for this field.

### Query parameters

Parameters

`options`

` object ( GetPolicyOptions  ` )

OPTIONAL: A `GetPolicyOptions` object for specifying options to `authProviders.getIamPolicy` .

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Policy  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
