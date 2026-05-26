---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools
title: 'REST Resource: locations.workforcePools'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: WorkforcePool](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools#WorkforcePool)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools#WorkforcePool.SCHEMA_REPRESENTATION)
  - [State](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools#State)
  - [AccessRestrictions](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools#AccessRestrictions)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools#AccessRestrictions.SCHEMA_REPRESENTATION)
  - [ServiceConfig](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools#ServiceConfig)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools#ServiceConfig.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools#METHODS_SUMMARY)

## Resource: WorkforcePool

Represents a collection of external workforces. Provides namespaces for federated users that can be referenced in IAM policies.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;parent&quot;: string,&quot;displayName&quot;: string,&quot;description&quot;: string,&quot;state&quot;: enum (State),&quot;disabled&quot;: boolean,&quot;sessionDuration&quot;: string,&quot;expireTime&quot;: string,&quot;accessRestrictions&quot;: {object (AccessRestrictions)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Identifier. The resource name of the pool.

Format: `locations/{location}/workforcePools/{workforcePoolId}`

`parent`

`string`

Immutable. The resource name of the parent.

Format: `organizations/{org-id}` .

`displayName`

`string`

Optional. A display name for the pool.

Cannot exceed 32 characters.

`description`

`string`

Optional. A description of the pool.

Cannot exceed 256 characters.

`state`

` enum ( State  ` )

Output only. The state of the pool.

`disabled`

`boolean`

Optional. Disables the workforce pool. You cannot use a disabled pool to exchange tokens, or use existing tokens to access resources. If the pool is re-enabled, existing tokens grant access again.

`sessionDuration`

` string ( Duration  ` format)

Optional. Duration that the Google Cloud access tokens, console sign-in sessions, and `gcloud` sign-in sessions from this pool are valid.

Must be greater than 15 minutes (900s) and less than 12 hours (43200s). If `sessionDuration` is not configured, minted credentials have a default duration of one hour (3600s).

For SAML providers, the lifetime of the token is the minimum of the `sessionDuration` and the `SessionNotOnOrAfter` claim in the SAML assertion.

A duration in seconds with up to nine fractional digits, ending with ' `s` '. Example: `"3.5s"` .

`expireTime`

` string ( Timestamp  ` format)

Output only. Time after which the workforce pool will be permanently purged and cannot be recovered.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`accessRestrictions`

` object ( AccessRestrictions  ` )

Optional. Configure access restrictions on the workforce pool users. This is an optional field. If specified web sign-in can be restricted to given set of services or programmatic sign-in can be disabled for pool users.

## State

The current state of the pool.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The pool is active and may be used in Google Cloud policies.

`DELETED`

The pool is soft-deleted. Soft-deleted pools are permanently deleted after approximately 30 days. You can restore a soft-deleted pool using `  workforcePools.undelete  ` .

You cannot reuse the ID of a soft-deleted pool until it is permanently deleted.

While a pool is deleted, you cannot use it to exchange tokens, or use existing tokens to access resources. If the pool is undeleted, existing tokens grant access again.

## AccessRestrictions

Access related restrictions on the workforce pool.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;allowedServices&quot;: [{object (ServiceConfig)}],&quot;disableProgrammaticSignin&quot;: boolean}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`allowedServices[]`

` object ( ServiceConfig  ` )

Optional. Immutable. Services allowed for web sign-in with the workforce pool. If not set by default there are no restrictions.

`disableProgrammaticSignin`

`boolean`

Optional. Disable programmatic sign-in by disabling token issue via the Security Token API endpoint. See [Security Token Service API](https://cloud.google.com/iam/docs/reference/sts/rest) .

## ServiceConfig

Configuration for a service.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{
  &quot;domain&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`domain`

`string`

Optional. Domain name of the service.

Example: console.cloud.google

## Methods

### `            create           `

Creates a new `  WorkforcePool  ` .

### `            delete           `

Deletes a `  WorkforcePool  ` .

### `            get           `

Gets an individual `  WorkforcePool  ` .

### `            getIamPolicy           `

Gets IAM policies on a `  WorkforcePool  ` .

### `            list           `

Lists all non-deleted `  WorkforcePool  ` s under the specified parent.

### `            patch           `

Updates an existing `  WorkforcePool  ` .

### `            setIamPolicy           `

Sets IAM policies on a `  WorkforcePool  ` .

### `            testIamPermissions           `

Returns the caller's permissions on the `  WorkforcePool  ` .

### `            undelete           `

Undeletes a `  WorkforcePool  ` , as long as it was deleted fewer than 30 days ago.
