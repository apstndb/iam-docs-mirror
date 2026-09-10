---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers.keys
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers.keys
title: 'REST Resource: projects.locations.workloadIdentityPools.providers.keys'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: WorkloadIdentityPoolProviderKey](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers.keys#WorkloadIdentityPoolProviderKey)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers.keys#WorkloadIdentityPoolProviderKey.SCHEMA_REPRESENTATION)
  - [State](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers.keys#State)
  - [KeyUse](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers.keys#KeyUse)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers.keys#METHODS_SUMMARY)

## Resource: WorkloadIdentityPoolProviderKey

Represents a public key configuration for your workload identity pool provider. The key can be configured in your identity provider to encrypt the SAML assertions. Google holds the corresponding private key which it uses to decrypt encrypted tokens.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;keyData&quot;: {object (KeyData)},&quot;state&quot;: enum (State),&quot;use&quot;: enum (KeyUse),&quot;expireTime&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Output only. The resource name of the key.

`keyData`

` object ( KeyData  ` )

Immutable. Public half of the asymmetric key.

`state`

` enum ( State  ` )

Output only. The state of the key.

`use`

` enum ( KeyUse  ` )

Required. The purpose of the key.

`expireTime`

` string ( Timestamp  ` format)

Output only. Time after which the key will be permanently purged and cannot be recovered. Note that the key may get purged before this timestamp if the total limit of keys per provider is crossed.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

## State

The current state of the key.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The key is active.

`DELETED`

The key is soft-deleted. Soft-deleted keys are permanently deleted after approximately 30 days. You can restore a soft-deleted key using `  keys.undelete  ` . While a key is deleted, you cannot use it during the federation.

## KeyUse

The uses for which a workload identity pool provider key might be generated. A key has exactly one use.

Enums

`KEY_USE_UNSPECIFIED`

The key use is not known.

`ENCRYPTION`

The public key is used for encryption purposes.

## Methods

### `            create           `

Create a new `  WorkloadIdentityPoolProviderKey  ` in a `  WorkloadIdentityPoolProvider  ` .

### `            delete           `

Deletes an `  WorkloadIdentityPoolProviderKey  ` .

### `            get           `

Gets an individual `  WorkloadIdentityPoolProviderKey  ` .

### `            list           `

Lists all non-deleted `  WorkloadIdentityPoolProviderKey  ` s in a project.

### `            undelete           `

Undeletes an `  WorkloadIdentityPoolProviderKey  ` , as long as it was deleted fewer than 30 days ago.
