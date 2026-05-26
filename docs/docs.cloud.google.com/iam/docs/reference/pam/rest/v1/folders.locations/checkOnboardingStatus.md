---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/checkOnboardingStatus
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/checkOnboardingStatus
title: 'Method: folders.locations.checkOnboardingStatus'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/checkOnboardingStatus#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/checkOnboardingStatus#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/checkOnboardingStatus#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/checkOnboardingStatus#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/checkOnboardingStatus#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/checkOnboardingStatus#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/checkOnboardingStatus#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/checkOnboardingStatus#try-it)

`locations.checkOnboardingStatus` reports the onboarding status for a project, folder, or organization. Any findings reported by this API need to be fixed before PAM can be used on the resource.

### HTTP request

`GET https://privilegedaccessmanager.googleapis.com/v1/{parent=folders/*/locations/*}:checkOnboardingStatus`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The resource for which the onboarding status should be checked. Should be in one of the following formats:

  - `projects/{project-number|project-id}/locations/{region}`
  - `folders/{folder-number}/locations/{region}`
  - `organizations/{organization-number}/locations/{region}`

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  CheckOnboardingStatusResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `privilegedaccessmanager.locations.checkOnboardingStatus`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
