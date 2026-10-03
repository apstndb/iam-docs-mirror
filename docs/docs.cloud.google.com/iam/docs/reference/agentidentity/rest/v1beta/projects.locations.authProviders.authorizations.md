---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders.authorizations
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders.authorizations
title: 'REST Resource: projects.locations.authProviders.authorizations'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: Authorization](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders.authorizations#Authorization)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders.authorizations#Authorization.SCHEMA_REPRESENTATION)
- [State](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders.authorizations#State)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders.authorizations#METHODS_SUMMARY)

## Resource: Authorization

Represents an authorization.

**JSON representation**

```
{
  "name": string,
  "createTime": string,
  "updateTime": string,
  "clientUserId": string,
  "scopes": [
    string
  ],
  "state": enum (State)
}
```

| Fields         |                                                                                                                                                                                                                                                                                                                                                                                                            |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`         | `string` Identifier. The resource name of the authorization.                                                                                                                                                                                                                                                                                                                                               |
| `createTime`   | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The creation timestamp. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` . |
| `updateTime`   | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The update timestamp. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .   |
| `clientUserId` | `string` Output only. The client user ID provided by the client application for their end user. Not verified by Google.                                                                                                                                                                                                                                                                                    |
| `scopes[]`     | `string` Output only. The scopes actually granted by the end user during the consent flow.                                                                                                                                                                                                                                                                                                                 |
| `state`        | `enum ( `[`State`](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders.authorizations#State)` )` Output only. The state of the authorization.                                                                                                                                                                                                      |

## State

Represents the state of the authorization.

| Enums               |                    |
|---------------------|--------------------|
| `STATE_UNSPECIFIED` | Unspecified state. |
| `ACTIVE`            | Active.            |
| `SUSPENDED`         | Suspended.         |

| Methods                                                                                                                                       |                                                       |
|-----------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders.authorizations/delete) | Deletes a single authorization.                       |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders.authorizations/get)       | Gets details of a single authorization.               |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders.authorizations/list)     | Lists authorizations in a given project and location. |
