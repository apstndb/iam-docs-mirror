---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/roles/queryGrantableRoles
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/queryGrantableRoles
title: 'Method: roles.queryGrantableRoles'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/queryGrantableRoles#body.HTTP_TEMPLATE)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/queryGrantableRoles#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/queryGrantableRoles#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/queryGrantableRoles#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/queryGrantableRoles#body.QueryGrantableRolesResponse.SCHEMA_REPRESENTATION)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/queryGrantableRoles#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/queryGrantableRoles#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/queryGrantableRoles#try-it)

Lists roles that can be granted on a Google Cloud resource. A role is grantable if the IAM policy for the resource can contain bindings to the role.

### HTTP request

`POST https://iam.googleapis.com/v1/roles:queryGrantableRoles`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "fullResourceName": string,
  "view": enum (RoleView),
  "pageSize": integer,
  "pageToken": string
}
```

| Fields             |                                                                                                                                                                                                                                                                                                   |
|--------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `fullResourceName` | `string` Required. Required. The full resource name to query from the list of grantable roles. The name follows the Google Cloud Platform resource format. For example, a Cloud Platform project with id `my-project` will be named `//cloudresourcemanager.googleapis.com/projects/my-project` . |
| `view`             | `enum ( `[`RoleView`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/RoleView)` )`                                                                                                                                                                                                      |
| `pageSize`         | `integer` Optional limit on the number of roles to include in the response. The default is 300, and the maximum is 2,000.                                                                                                                                                                         |
| `pageToken`        | `string` Optional pagination token returned in an earlier QueryGrantableRolesResponse.                                                                                                                                                                                                            |

### Response body

The grantable role query response.

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "roles": [
    {
      object (Role)
    }
  ],
  "nextPageToken": string
}
```

| Fields          |                                                                                                                                        |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------|
| `roles[]`       | `object ( `[`Role`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role)` )` The list of matching roles. |
| `nextPageToken` | `string` To retrieve the next page of results, set `QueryGrantableRolesRequest.page_token` to this value.                              |

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
