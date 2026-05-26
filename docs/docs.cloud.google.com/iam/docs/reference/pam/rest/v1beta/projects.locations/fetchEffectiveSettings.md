---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/fetchEffectiveSettings
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/fetchEffectiveSettings
title: 'Method: projects.locations.fetchEffectiveSettings'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/fetchEffectiveSettings#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/fetchEffectiveSettings#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/fetchEffectiveSettings#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/fetchEffectiveSettings#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/fetchEffectiveSettings#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/fetchEffectiveSettings#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/fetchEffectiveSettings#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/fetchEffectiveSettings#try-it)

`locations.fetchEffectiveSettings` returns the effective PAM Settings for the given project, folder, or organization.

### HTTP request

`GET https://privilegedaccessmanager.googleapis.com/v1beta/{parent=projects/*/locations/*}:fetchEffectiveSettings`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The resource for which the effective settings is fetched, in one of the following formats:

  - `projects/{project-number|project-id}/locations/{region}`
  - `folders/{folder-number}/locations/{region}`
  - `organizations/{organization-number}/locations/{region}`

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  FetchEffectiveSettingsResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `privilegedaccessmanager.settings.fetchEffective`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
