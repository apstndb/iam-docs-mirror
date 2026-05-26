---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities
title: 'REST Resource: projects.locations.workloadIdentityPools.namespaces.managedIdentities'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: WorkloadIdentityPoolManagedIdentity](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities#WorkloadIdentityPoolManagedIdentity)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities#WorkloadIdentityPoolManagedIdentity.SCHEMA_REPRESENTATION)
  - [State](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities#State)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities#METHODS_SUMMARY)

## Resource: WorkloadIdentityPoolManagedIdentity

Represents a managed identity for a workload identity pool namespace.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;description&quot;: string,&quot;state&quot;: enum (State),&quot;disabled&quot;: boolean,&quot;expireTime&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Output only. The resource name of the managed identity.

`description`

`string`

Optional. A description of the managed identity. Cannot exceed 256 characters.

`state`

` enum ( State  ` )

Output only. The state of the managed identity.

`disabled`

`boolean`

Optional. Whether the managed identity is disabled. If disabled, credentials may no longer be issued for the identity, however existing credentials will still be accepted until they expire.

`expireTime`

` string ( Timestamp  ` format)

Output only. Time after which the managed identity will be permanently purged and cannot be recovered.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

## State

The current state of the managed identity.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The managed identity is active.

`DELETED`

The managed identity is soft-deleted. Soft-deleted managed identities are permanently deleted after approximately 30 days. You can restore a soft-deleted managed identity using `  managedIdentities.undelete  ` .

You cannot reuse the ID of a soft-deleted managed identity until it is permanently deleted.

## Methods

### `            addAttestationRule           `

Add an `  AttestationRule  ` on a `  WorkloadIdentityPoolManagedIdentity  ` .

### `            create           `

Creates a new `  WorkloadIdentityPoolManagedIdentity  ` in a `  WorkloadIdentityPoolNamespace  ` .

### `            delete           `

Deletes a `  WorkloadIdentityPoolManagedIdentity  ` .

### `            get           `

Gets an individual `  WorkloadIdentityPoolManagedIdentity  ` .

### `            list           `

Lists all non-deleted `  WorkloadIdentityPoolManagedIdentity  ` s in a namespace.

### `            listAttestationRules           `

List all `  AttestationRule  ` on a `  WorkloadIdentityPoolManagedIdentity  ` .

### `            patch           `

Updates an existing `  WorkloadIdentityPoolManagedIdentity  ` in a `  WorkloadIdentityPoolNamespace  ` .

### `            removeAttestationRule           `

Remove an `  AttestationRule  ` on a `  WorkloadIdentityPoolManagedIdentity  ` .

### `            setAttestationRules           `

Set all `  AttestationRule  ` on a `  WorkloadIdentityPoolManagedIdentity  ` .

### `            undelete           `

Undeletes a `  WorkloadIdentityPoolManagedIdentity  ` , as long as it was deleted fewer than 30 days ago.
