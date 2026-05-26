---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/patch
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/patch
title: 'Method: projects.locations.entitlements.patch'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/patch#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/patch#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/patch#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/patch#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/patch#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/patch#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/patch#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/patch#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/patch#try-it)

Updates the entitlement specified in the request. Updated fields in the entitlement need to be specified in an update mask. The changes made to an entitlement are applicable only on future grants of the entitlement. However, if new approvers are added or existing approvers are removed from the approval workflow, the changes are effective on existing grants.

The following fields are not supported for updates:

  - All immutable fields
  - Entitlement name
  - Resource name
  - Resource type
  - Adding an approval workflow in an entitlement which previously had no approval workflow.
  - Deleting the approval workflow from an entitlement.
  - Adding or deleting a step in the approval workflow (only one step is supported)

Note that updates are allowed on the list of approvers in an approval workflow step.

### HTTP request

`PATCH https://privilegedaccessmanager.googleapis.com/v1beta/{entitlement.name=projects/*/locations/*/entitlements/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`entitlement.name`

`string`

Identifier. Name of the entitlement. Possible formats:

  - `organizations/{organization-number}/locations/{region}/entitlements/{entitlement-id}`
  - `folders/{folder-number}/locations/{region}/entitlements/{entitlement-id}`
  - `projects/{project-id|project-number}/locations/{region}/entitlements/{entitlement-id}`

### Query parameters

Parameters

`updateMask`

` string ( FieldMask  ` format)

Required. The list of fields to update. A field is overwritten if, and only if, it is in the mask. Any immutable fields set in the mask are ignored by the server. Repeated fields and map fields are only allowed in the last position of a `paths` string and overwrite the existing values. Hence an update to a repeated field or a map should contain the entire list of values. The fields specified in the updateMask are relative to the resource and not to the request. (e.g. `MaxRequestDuration` ; *not* `entitlement.MaxRequestDuration` ) A value of '\*' for this field refers to full replacement of the resource.

This is a comma-separated list of fully qualified names of fields. Example: `"user.displayName,photo"` .

### Request body

The request body contains an instance of `  Entitlement  ` .

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `privilegedaccessmanager.entitlements.update`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
