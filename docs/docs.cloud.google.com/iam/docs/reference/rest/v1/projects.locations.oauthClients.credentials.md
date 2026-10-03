---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials
title: 'REST Resource: projects.locations.oauthClients.credentials'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: OauthClientCredential](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential.SCHEMA_REPRESENTATION)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#METHODS_SUMMARY)

## Resource: OauthClientCredential

Represents an [`OauthClientCredential`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential) . Used to authenticate an [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) while accessing Google Cloud resources on behalf of a user by using OAuth 2.0 Protocol.

**JSON representation**

```
{
  "name": string,
  "disabled": boolean,
  "displayName": string,

  // Union field credential can be only one of the following:
  "clientSecret": string
  // End of list of possible types for union field credential.
}
```

| Fields                                                                    |                                                                                                                                                                                                                                                                                                                                                                                      |
|---------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`                                                                    | `string` Immutable. Identifier. The resource name of the [`OauthClientCredential`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential) . Format: `projects/{project}/locations/{location}/oauthClients/{oauthClient}/credentials/{credential}`                                                               |
| `disabled`                                                                | `boolean` Optional. Whether the [`OauthClientCredential`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential) is disabled. You cannot use a disabled [`OauthClientCredential`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential) . |
| `displayName`                                                             | `string` Optional. A user-specified display name of the [`OauthClientCredential`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential) . Cannot exceed 32 characters.                                                                                                                                         |
| Union field `credential` . `credential` can be only one of the following: |                                                                                                                                                                                                                                                                                                                                                                                      |
| `clientSecret`                                                            | `string` Output only. The system-generated OAuth client secret. The client secret must be stored securely. If the client secret is leaked, you must delete and re-create the client credential. To learn more, see [OAuth client and credential security risks and mitigations](https://cloud.google.com/iam/docs/workforce-oauth-app#security)                                      |

| Methods                                                                                                                 |                                                                                                                                                                                                                                                                                                 |
|-------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials/create) | Creates a new [`OauthClientCredential`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential) .                                                                                                                           |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials/delete) | Deletes an [`OauthClientCredential`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential) .                                                                                                                              |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials/get)       | Gets an individual [`OauthClientCredential`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential) .                                                                                                                      |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials/list)     | Lists all [`OauthClientCredential`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential) s in an [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) . |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials/patch)   | Updates an existing [`OauthClientCredential`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential) .                                                                                                                     |
