---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/revokeSessions
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/revokeSessions
title: 'Method: locations.workforcePools.subjects.revokeSessions'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/revokeSessions#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/revokeSessions#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/revokeSessions#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/revokeSessions#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/revokeSessions#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/revokeSessions#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/revokeSessions#try-it)

Revokes all sessions for the specified `WorkforcePoolSubject` . Revoking sessions invalidates all active sessions and previously issued credentials for the subject, requiring the user to re-authenticate with the identity provider.

### HTTP request

`POST https://iam.googleapis.com/v1/{name=locations/*/workforcePools/*/subjects/*}:revokeSessions`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                                                                                                                                                                                                                                                                                                            |
|------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`     | `string` Required. The resource name of the `WorkforcePoolSubject` . Special characters, such as `/` and `:` , must be escaped, because all URLs must conform to the "When to Escape and Unescape" section of [RFC 3986](https://www.rfc-editor.org/info/rfc3986/) . Format: `locations/{location}/workforcePools/{workforcePoolId}/subjects/{subject_id}` |

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`Operation`](https://docs.cloud.google.com/iam/docs/reference/rest/Shared.Types/Operation) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
