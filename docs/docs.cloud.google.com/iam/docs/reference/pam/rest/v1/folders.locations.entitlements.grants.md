---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants
title: 'REST Resource: folders.locations.entitlements.grants'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: Grant](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.SCHEMA_REPRESENTATION)
      - [Justification](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Justification)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Justification.SCHEMA_REPRESENTATION)
      - [State](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.State)
      - [Timeline](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Timeline)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Timeline.SCHEMA_REPRESENTATION)
      - [Event](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Event)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Event.SCHEMA_REPRESENTATION)
      - [Requested](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Requested)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Requested.SCHEMA_REPRESENTATION)
      - [Approved](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Approved)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Approved.SCHEMA_REPRESENTATION)
      - [Denied](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Denied)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Denied.SCHEMA_REPRESENTATION)
      - [Revoked](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Revoked)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Revoked.SCHEMA_REPRESENTATION)
      - [Scheduled](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Scheduled)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Scheduled.SCHEMA_REPRESENTATION)
      - [Activated](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Activated)
      - [ActivationFailed](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.ActivationFailed)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.ActivationFailed.SCHEMA_REPRESENTATION)
      - [Expired](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Expired)
      - [Ended](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Ended)
      - [ExternallyModified](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.ExternallyModified)
      - [Withdrawn](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.Withdrawn)
      - [AuditTrail](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.AuditTrail)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#Grant.AuditTrail.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants#METHODS_SUMMARY)

## Resource: Grant

A grant represents a request from a user for obtaining the access specified in an entitlement they are eligible for.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;createTime&quot;: string,&quot;updateTime&quot;: string,&quot;requester&quot;: string,&quot;requestedDuration&quot;: string,&quot;justification&quot;: {object (Justification)},&quot;state&quot;: enum (State),&quot;timeline&quot;: {object (Timeline)},&quot;privilegedAccess&quot;: {object (PrivilegedAccess)},&quot;auditTrail&quot;: {object (AuditTrail)},&quot;additionalEmailRecipients&quot;: [string],&quot;externallyModified&quot;: boolean}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Identifier. Name of this grant. Possible formats:

  - `organizations/{organization-number}/locations/{region}/entitlements/{entitlement-id}/grants/{grant-id}`
  - `folders/{folder-number}/locations/{region}/entitlements/{entitlement-id}/grants/{grant-id}`
  - `projects/{project-id|project-number}/locations/{region}/entitlements/{entitlement-id}/grants/{grant-id}`

The last segment of this name ( `{grant-id}` ) is autogenerated.

`createTime`

` string ( Timestamp  ` format)

Output only. Create time stamp.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`updateTime`

` string ( Timestamp  ` format)

Output only. Update time stamp.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`requester`

`string`

Output only. Username of the user who created this grant.

`requestedDuration`

` string ( Duration  ` format)

Required. The amount of time access is needed for. This value should be shorter than the `maxRequestDuration` value of the entitlement.

A duration in seconds with up to nine fractional digits, ending with ' `s` '. Example: `"3.5s"` .

`justification`

` object ( Justification  ` )

Optional. Justification of why this access is needed.

`state`

` enum ( State  ` )

Output only. Current state of this grant.

`timeline`

` object ( Timeline  ` )

Output only. Timeline of this grant.

`privilegedAccess`

` object ( PrivilegedAccess  ` )

Output only. The access that would be granted by this grant.

`auditTrail`

` object ( AuditTrail  ` )

Output only. Audit trail of access provided by this grant. If unspecified then access was never granted.

`additionalEmailRecipients[]`

`string`

Optional. Additional email addresses to notify for all the actions performed on the grant.

`externallyModified`

`boolean`

Output only. Flag set by the PAM system to indicate that policy bindings made by this grant have been modified from outside PAM.

After it is set, this flag remains set forever irrespective of the grant state. A `true` value here indicates that PAM no longer has any certainty on the access a user has because of this grant.

### Justification

Justification represents a justification for requesting access.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field justification can be only one of the following:&quot;unstructuredJustification&quot;: string// End of list of possible types for union field justification.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `justification` .

`justification` can be only one of the following:

`unstructuredJustification`

`string`

A free form textual justification. The system only ensures that this is not empty. No other kind of validation is performed on the string.

### State

Different states a grant can be in.

Enums

`STATE_UNSPECIFIED`

Unspecified state. This value is never returned by the server.

`APPROVAL_AWAITED`

The entitlement had an approval workflow configured and this grant is waiting for the workflow to complete.

`DENIED`

The approval workflow completed with a denied result. No access is granted for this grant. This is a terminal state.

`SCHEDULED`

The approval workflow completed successfully with an approved result or none was configured. Access is provided at an appropriate time.

`ACTIVATING`

Access is being given.

`ACTIVE`

Access was successfully given and is currently active.

`ACTIVATION_FAILED`

The system could not give access due to a non-retriable error. This is a terminal state.

`EXPIRED`

Expired after waiting for the approval workflow to complete. This is a terminal state.

`REVOKING`

Access is being revoked.

`REVOKED`

Access was revoked by a user. This is a terminal state.

`ENDED`

System took back access as the requested duration was over. This is a terminal state.

`WITHDRAWING`

Access is being withdrawn.

`WITHDRAWN`

Grant was withdrawn by the grant owner. This is a terminal state.

### Timeline

Timeline of a grant describing what happened to it and when.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;events&quot;: [{object (Event)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`events[]`

` object ( Event  ` )

Output only. The events that have occurred on this grant. This list contains entries in the same order as they occurred. The first entry is always be of type `Requested` and there is always at least one entry in this array.

### Event

A single operation on the grant.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;eventTime&quot;: string,// Union field event can be only one of the following:&quot;requested&quot;: {object (Requested)},&quot;approved&quot;: {object (Approved)},&quot;denied&quot;: {object (Denied)},&quot;revoked&quot;: {object (Revoked)},&quot;scheduled&quot;: {object (Scheduled)},&quot;activated&quot;: {object (Activated)},&quot;activationFailed&quot;: {object (ActivationFailed)},&quot;expired&quot;: {object (Expired)},&quot;ended&quot;: {object (Ended)},&quot;externallyModified&quot;: {object (ExternallyModified)},&quot;withdrawn&quot;: {object (Withdrawn)}// End of list of possible types for union field event.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`eventTime`

` string ( Timestamp  ` format)

Output only. The time (as recorded at server) when this event occurred.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

Union field `event` .

`event` can be only one of the following:

`requested`

` object ( Requested  ` )

The grant was requested.

`approved`

` object ( Approved  ` )

The grant was approved.

`denied`

` object ( Denied  ` )

The grant was denied.

`revoked`

` object ( Revoked  ` )

The grant was revoked.

`scheduled`

` object ( Scheduled  ` )

The grant has been scheduled to give access.

`activated`

` object ( Activated  ` )

The grant was successfully activated to give access.

`activationFailed`

` object ( ActivationFailed  ` )

There was a non-retriable error while trying to give access.

`expired`

` object ( Expired  ` )

The approval workflow did not complete in the necessary duration, and so the grant is expired.

`ended`

` object ( Ended  ` )

Access given by the grant ended automatically as the approved duration was over.

`externallyModified`

` object ( ExternallyModified  ` )

The policy bindings made by grant have been modified outside of PAM.

`withdrawn`

` object ( Withdrawn  ` )

The grant was withdrawn.

### Requested

An event representing that a grant was requested.

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
  &quot;expireTime&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`expireTime`

` string ( Timestamp  ` format)

Output only. The time at which this grant expires unless the approval workflow completes. If omitted, then the request never expires.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

### Approved

An event representing that the grant was approved.

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
  &quot;reason&quot;: string,
  &quot;actor&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`reason`

`string`

Output only. The reason provided by the approver for approving the grant.

`actor`

`string`

Output only. Username of the user who approved the grant.

### Denied

An event representing that the grant was denied.

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
  &quot;reason&quot;: string,
  &quot;actor&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`reason`

`string`

Output only. The reason provided by the approver for denying the grant.

`actor`

`string`

Output only. Username of the user who denied the grant.

### Revoked

An event representing that the grant was revoked.

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
  &quot;reason&quot;: string,
  &quot;actor&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`reason`

`string`

Output only. The reason provided by the user for revoking the grant.

`actor`

`string`

Output only. Username of the user who revoked the grant.

### Scheduled

An event representing that the grant has been scheduled to be activated later.

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
  &quot;scheduledActivationTime&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`scheduledActivationTime`

` string ( Timestamp  ` format)

Output only. The time at which the access is granted.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

### Activated

This type has no fields.

An event representing that the grant was successfully activated.

### ActivationFailed

An event representing that the grant activation failed.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;error&quot;: {object (Status)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`error`

` object ( Status  ` )

Output only. The error that occurred while activating the grant.

### Expired

This type has no fields.

An event representing that the grant was expired.

### Ended

This type has no fields.

An event representing that the grant has ended.

### ExternallyModified

This type has no fields.

An event representing that the policy bindings made by this grant were modified externally.

### Withdrawn

This type has no fields.

An event representing that the grant was withdrawn.

### AuditTrail

Audit trail for the access provided by this grant.

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
  &quot;accessGrantTime&quot;: string,
  &quot;accessRemoveTime&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`accessGrantTime`

` string ( Timestamp  ` format)

Output only. The time at which access was given.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`accessRemoveTime`

` string ( Timestamp  ` format)

Output only. The time at which the system removed access. This could be because of an automatic expiry or because of a revocation.

If unspecified, then access hasn't been removed yet.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

## Methods

### `            approve           `

`ApproveGrant` is used to approve a grant.

### `            create           `

Creates a grant in a given project, folder, or organization and location.

### `            deny           `

`DenyGrant` is used to deny a grant.

### `            get           `

Get details of a single grant.

### `            list           `

Lists grants for a given entitlement.

### `            revoke           `

`RevokeGrant` is used to immediately revoke access for a grant.

### `            search           `

`SearchGrants` returns grants that are related to the calling user in the specified way.
