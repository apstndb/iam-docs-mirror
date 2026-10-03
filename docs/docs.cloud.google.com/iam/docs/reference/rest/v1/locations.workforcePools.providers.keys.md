---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys
title: 'REST Resource: locations.workforcePools.providers.keys'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: WorkforcePoolProviderKey](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys#WorkforcePoolProviderKey)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys#WorkforcePoolProviderKey.SCHEMA_REPRESENTATION)
- [State](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys#State)
- [KeyUse](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys#KeyUse)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys#METHODS_SUMMARY)

## Resource: WorkforcePoolProviderKey

Represents a public key configuration for a Workforce Pool Provider. The key can be configured in your identity provider to encrypt SAML assertions. Google holds the corresponding private key, which it uses to decrypt encrypted tokens.

**JSON representation**

```
{
  "name": string,
  "keyData": {
    object (KeyData)
  },
  "state": enum (State),
  "use": enum (KeyUse),
  "expireTime": string
}
```

| Fields       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`       | `string` Identifier. The resource name of the key. Format: `locations/{location}/workforcePools/{workforcePoolId}/providers/{providerId}/keys/{keyId}`                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `keyData`    | `object ( `[`KeyData`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/KeyData)` )` Immutable. Public half of the asymmetric key.                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `state`      | `enum ( `[`State`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys#State)` )` Output only. The state of the key.                                                                                                                                                                                                                                                                                                                                                                                                           |
| `use`        | `enum ( `[`KeyUse`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys#KeyUse)` )` Required. The purpose of the key.                                                                                                                                                                                                                                                                                                                                                                                                          |
| `expireTime` | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The time after which the key will be permanently deleted and cannot be recovered. Note that the key may get purged before this time if the total limit of keys per provider is exceeded. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` . |

## State

The current state of the key.

| Enums               |                                                                                                                                                                                                                                                                                                                                             |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `STATE_UNSPECIFIED` | State unspecified.                                                                                                                                                                                                                                                                                                                          |
| `ACTIVE`            | The key is active.                                                                                                                                                                                                                                                                                                                          |
| `DELETED`           | The key is soft-deleted. Soft-deleted keys are permanently deleted after approximately 30 days. You can restore a soft-deleted key using [`keys.undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys/undelete#google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePoolProviderKey) . |

## KeyUse

The purpose of the key.

| Enums                 |                                                                           |
|-----------------------|---------------------------------------------------------------------------|
| `KEY_USE_UNSPECIFIED` | KeyUse unspecified. Do not use. The purpose of the key must be specified. |
| `ENCRYPTION`          | The key is used for encryption.                                           |

| Methods                                                                                                                 |                                                                                                                                                                                                                                                                                                                                     |
|-------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys/create)     | Creates a new [`WorkforcePoolProviderKey`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys#WorkforcePoolProviderKey) in a [`WorkforcePoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WorkforcePoolProvider) .           |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys/delete)     | Deletes a [`WorkforcePoolProviderKey`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys#WorkforcePoolProviderKey) .                                                                                                                                                                 |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys/get)           | Gets a [`WorkforcePoolProviderKey`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys#WorkforcePoolProviderKey) .                                                                                                                                                                    |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys/list)         | Lists all non-deleted [`WorkforcePoolProviderKey`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys#WorkforcePoolProviderKey) s in a [`WorkforcePoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WorkforcePoolProvider) . |
| [`undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys/undelete) | Undeletes a [`WorkforcePoolProviderKey`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.keys#WorkforcePoolProviderKey) , as long as it was deleted fewer than 30 days ago.                                                                                                             |
