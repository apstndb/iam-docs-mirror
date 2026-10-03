---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve
title: 'Method: projects.locations.authProviders.credentials.retrieve'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#body.RetrieveCredentialsResponse.SCHEMA_REPRESENTATION)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#body.aspect)
- [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#body.aspect_1)
- [Success](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#Success)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#Success.SCHEMA_REPRESENTATION)
- [Pending](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#Pending)
- [UriConsentRequired](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#UriConsentRequired)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#UriConsentRequired.SCHEMA_REPRESENTATION)
- [ConsentRejected](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#ConsentRejected)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#try-it)

Retrieves authorization credentials for an auth provider, or indicates what action needs to be taken to obtain credentials. If the `token` field in the response is populated, credential retrieval was successful. If one of the fields in the `result` oneof is populated, further action is required to obtain credentials, such as redirecting the user for consent. View comments on `RetrieveCredentialsResponse` for more information.

### HTTP request

`POST https://agentidentitycredentials.googleapis.com/v1/{authProvider=projects/*/locations/*/authProviders/*}/credentials:retrieve`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters     |                                                                                                                                                  |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| `authProvider` | `string` Required. The parent resource name of the auth provider. Format: `projects/{project}/locations/{location}/authProviders/{authProvider}` |

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "userId": string,
  "scopes": [
    string
  ],
  "continueUri": string,
  "forceRefreshToken": string
}
```

| Fields              |                                                                                                                                                                                                                                                                                            |
|---------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `userId`            | `string` Required. The identity of the end user.                                                                                                                                                                                                                                           |
| `scopes[]`          | `string` Optional. The OAuth scopes required for this access.                                                                                                                                                                                                                              |
| `continueUri`       | `string` Optional. The URI to redirect the user to after consent is completed. This field is required for auth providers using the 3-legged OAuth flow. For other auth provider types, this field is unused but not rejected.                                                              |
| `forceRefreshToken` | `string` Optional. Input only. Set this field only if the previous token was expired or invalid. This value must be the full, previously returned token string. Setting this field triggers a refresh of the access token with a stored refresh token, if possible, or a new consent flow. |

### Response body

Response message for credentials.retrieve. Contains the access tokens and related artifacts.

If successful, the response body contains data with the following structure:

**JSON representation**

```
{

  // Union field result can be only one of the following:
  "success": {
    object (Success)
  },
  "pending": {
    object (Pending)
  },
  "uriConsentRequired": {
    object (UriConsentRequired)
  },
  "consentRejected": {
    object (ConsentRejected)
  }
  // End of list of possible types for union field result.
}
```

| Fields                                                                                                                                                                                                                                                                                                                             |                                                                                                                                                                                                                                                     |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `result` . The result of the RetrieveCredentials call. This oneof indicates whether credentials were successfully retrieved, or what action needs to be taken. Note: All polling or retries should follow an exponential backoff (seconds): `0.5` , `1` , `2` , `4` , `8` . `result` can be only one of the following: |                                                                                                                                                                                                                                                     |
| `success`                                                                                                                                                                                                                                                                                                                          | `object ( `[`Success`](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#Success)` )` Message indicating credentials were successfully retrieved.             |
| `pending`                                                                                                                                                                                                                                                                                                                          | `object ( `[`Pending`](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#Pending)` )` Message indicating credential retrieval is pending.                     |
| `uriConsentRequired`                                                                                                                                                                                                                                                                                                               | `object ( `[`UriConsentRequired`](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#UriConsentRequired)` )` Message indicating URI-based consent is required. |
| `consentRejected`                                                                                                                                                                                                                                                                                                                  | `object ( `[`ConsentRejected`](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#ConsentRejected)` )` Message indicating consent was rejected.                |

### Authorization scopes

Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `authProvider` resource:

- `agentidentity.authProviders.retrieveCredentials`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

## Success

Message indicating successful retrieval of credentials.

**JSON representation**

```
{
  "token": string,
  "header": string,
  "expireTime": string,
  "scopes": [
    string
  ]
}
```

| Fields       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|--------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `token`      | `string` The retrieved access token or credential for the end user. On an MCP tool call, for an invalid token the OAuth spec states that this should return `401` or `403` , but MCP servers may implement this differently. If you get any flavor of `PERMISSION_DENIED` , retry your original request to `credentials.retrieve` with `forceRefreshToken` set to the expired/invalid token string, which will fetch a new token or initiate a new consent flow.                                                                                                                                                                                                                                                                                         |
| `header`     | `string` The HTTP header name where the token should be placed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `expireTime` | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` The expiration time of the token. This does not guarantee that the token will be valid until this time, since the token could be revoked earlier. There could also be clock skew between the auth provider and the client so it may expire slightly earlier. If not set, the token might be permanent or it may be that the service does not (or cannot) know when it will expire. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` . |
| `scopes[]`   | `string` The scopes actually associated with the retrieved token. End users may have rejected some requested scopes, or the third-party authorization servers can return a different set of scopes than what was asked for. Callers should verify that all required scopes for their intended use are included in this list.                                                                                                                                                                                                                                                                                                                                                                                                                             |

## Pending

This type has no fields.

Indicates that the credential retrieval is pending. The caller should retry the credentials.retrieve request after some time.

## UriConsentRequired

Indicates that the user must visit the provided URI to consent to delegate permission to the agent to act on their behalf. The caller can either poll the `credentials.retrieve` method, or await the /ValidateUserId callback.

**JSON representation**

```
{
  "authorizationUri": string,
  "consentNonce": string,
  "uid": string
}
```

| Fields             |                                                                                                                                                                                                                                                                                                                                                                                |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `authorizationUri` | `string` Output only. The URL where the user should be redirected to grant consent. This will always be present.                                                                                                                                                                                                                                                               |
| `consentNonce`     | `string` Output only. A one-time, randomly generated value that validates the entire consent flow is handled by a single user, avoiding CSRF attacks. It must be submitted with the credentials.finalize request to complete the OAuth exchange. This will always be present. Implemented per [RFC 6819 Section 5.3.5](https://www.rfc-editor.org/rfc/rfc6819#section-5.3.5) . |
| `uid`              | `string` Output only. The unique ID of the credentials retrieval operation.                                                                                                                                                                                                                                                                                                    |

## ConsentRejected

This type has no fields.

Indicates the user has rejected the permission delegation or canceled the request.
