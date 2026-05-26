---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/getSettings
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/getSettings
title: 'Method: organizations.locations.getSettings'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/getSettings#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/getSettings#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/getSettings#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/getSettings#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/getSettings#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/getSettings#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/getSettings#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/getSettings#try-it)

`locations.getSettings` returns the PAM Settings for the given project, folder, or organization.

### HTTP request

`GET https://privilegedaccessmanager.googleapis.com/v1beta/{name=organizations/*/locations/*/settings}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The name of the settings resource to be fetched.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Settings  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `privilegedaccessmanager.settings.get`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
