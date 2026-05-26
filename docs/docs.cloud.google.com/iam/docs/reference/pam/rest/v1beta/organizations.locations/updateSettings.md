---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/updateSettings
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/updateSettings
title: 'Method: organizations.locations.updateSettings'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/updateSettings#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/updateSettings#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/updateSettings#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/updateSettings#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/updateSettings#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/updateSettings#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/updateSettings#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/updateSettings#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/updateSettings#try-it)

`locations.updateSettings` updates the PAM Settings resource specified in the request. Updated fields in the settings need to be specified in an update mask. The following fields are not supported for updates: \* Settings name \* Create time \* Update time \* Etag

### HTTP request

`PATCH https://privilegedaccessmanager.googleapis.com/v1beta/{settings.name=organizations/*/locations/*/settings}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`settings.name`

`string`

Identifier. Name of the settings resource. Possible formats: projects/{project-id|project-number}/locations/{location}/settings folders/{folder-number}/locations/{location}/settings organizations/{organization-number}/locations/{location}/settings

### Query parameters

Parameters

`updateMask`

` string ( FieldMask  ` format)

Required. The list of fields to update. A field is overwritten if, and only if, it is in the mask. Any immutable fields set in the mask are ignored by the server. Repeated fields and map fields are only allowed in the last position of a `paths` string and overwrite the existing values. Hence an update to a repeated field or a map should contain the entire list of values. The fields specified in the updateMask are relative to the resource and not to the request. A value of '\*' for this field refers to full replacement of the resource.

This is a comma-separated list of fully qualified names of fields. Example: `"user.displayName,photo"` .

### Request body

The request body contains an instance of `  Settings  ` .

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `privilegedaccessmanager.settings.update`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
