---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens
title: 'REST Resource: locations.workforcePools.providers.scimTenants.tokens'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: WorkforcePoolProviderScimToken](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens#WorkforcePoolProviderScimToken)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens#WorkforcePoolProviderScimToken.SCHEMA_REPRESENTATION)
- [State](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens#State)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens#METHODS_SUMMARY)

## Resource: WorkforcePoolProviderScimToken

Gemini Enterprise only. Represents a token for the [`WorkforcePoolProviderScimTenant`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants#WorkforcePoolProviderScimTenant) . Used for authenticating SCIM provisioning requests.

**JSON representation**

```
{
  "name": string,
  "securityToken": string,
  "state": enum (State),
  "displayName": string
}
```

| Fields          |                                                                                                                                                                                                                             |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`          | `string` Identifier. Gemini Enterprise only. The resource name of the SCIM Token. Format: `locations/{location}/workforcePools/{workforcePool}/providers/ {workforcePoolProvider}/scimTenants/{scim_tenant}/tokens/{token}` |
| `securityToken` | `string` Output only. Gemini Enterprise only. The token string. Provide this to the IdP for authentication. Will be set only during creation.                                                                               |
| `state`         | `enum ( `[`State`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens#State)` )` Output only. Gemini Enterprise only. The state of the token.                   |
| `displayName`   | `string` Optional. Gemini Enterprise only. The display name of the SCIM token. Cannot exceed 32 characters.                                                                                                                 |

## State

Gemini Enterprise only. The current state of the SCIM token.

| Enums               |                                                                                                                             |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------|
| `STATE_UNSPECIFIED` | Gemini Enterprise only. State unspecified.                                                                                  |
| `ACTIVE`            | Gemini Enterprise only. The token is active and may be used to provision users and groups.                                  |
| `DELETED`           | Gemini Enterprise only. The token is soft-deleted. Soft-deleted tokens are permanently deleted after approximately 30 days. |

| Methods                                                                                                                               |                         |
|---------------------------------------------------------------------------------------------------------------------------------------|-------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/create)     | Gemini Enterprise only. |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/delete)     | Gemini Enterprise only. |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/get)           | Gemini Enterprise only. |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/list)         | Gemini Enterprise only. |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/patch)       | Gemini Enterprise only. |
| [`undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/undelete) | Gemini Enterprise only. |
