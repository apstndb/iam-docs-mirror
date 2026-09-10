---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements
title: 'REST Resource: projects.locations.entitlements'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: Entitlement](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements#Entitlement)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements#Entitlement.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements#METHODS_SUMMARY)

## Resource: Entitlement

An entitlement defines the eligibility of a set of users to obtain predefined access for some time possibly after going through an approval workflow.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;createTime&quot;: string,&quot;updateTime&quot;: string,&quot;eligibleUsers&quot;: [{object (AccessControlEntry)}],&quot;approvalWorkflow&quot;: {object (ApprovalWorkflow)},&quot;privilegedAccess&quot;: {object (PrivilegedAccess)},&quot;maxRequestDuration&quot;: string,&quot;state&quot;: enum (State),&quot;requesterJustificationConfig&quot;: {object (RequesterJustificationConfig)},&quot;additionalNotificationTargets&quot;: {object (AdditionalNotificationTargets)},&quot;etag&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Identifier. Name of the entitlement. Possible formats:

  - `organizations/{organization-number}/locations/{region}/entitlements/{entitlement-id}`
  - `folders/{folder-number}/locations/{region}/entitlements/{entitlement-id}`
  - `projects/{project-id|project-number}/locations/{region}/entitlements/{entitlement-id}`

`createTime`

` string ( Timestamp  ` format)

Output only. Create time stamp.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`updateTime`

` string ( Timestamp  ` format)

Output only. Update time stamp.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`eligibleUsers[]`

` object ( AccessControlEntry  ` )

Optional. Who can create grants using this entitlement. This list should contain at most one entry.

`approvalWorkflow`

` object ( ApprovalWorkflow  ` )

Optional. The approvals needed before access are granted to a requester. No approvals are needed if this field is null.

`privilegedAccess`

` object ( PrivilegedAccess  ` )

Required. The access granted to a requester on successful approval.

`maxRequestDuration`

` string ( Duration  ` format)

Required. The maximum amount of time that access is granted for a request. A requester can ask for a shorter duration but never a longer one. The supported range is between 30 minutes and 168 hours (7 days).

A duration in seconds with up to nine fractional digits, ending with ' `s` '. Example: `"3.5s"` .

`state`

` enum ( State  ` )

Output only. Current state of this entitlement.

`requesterJustificationConfig`

` object ( RequesterJustificationConfig  ` )

Required. The manner in which the requester should provide a justification for requesting access.

`additionalNotificationTargets`

` object ( AdditionalNotificationTargets  ` )

Optional. Additional email addresses to be notified based on actions taken.

`etag`

`string`

An `etag` is used for optimistic concurrency control as a way to prevent simultaneous updates to the same entitlement. An `etag` is returned in the response to `entitlements.get` and the caller should put the `etag` in the request to `entitlements.patch` so that their change is applied on the same version. If this field is omitted or if there is a mismatch while updating an entitlement, then the server rejects the request.

## Methods

### `            create           `

Creates a new entitlement in a given project, folder, organization, and in a given location.

### `            delete           `

Deletes a single entitlement.

### `            get           `

Gets details of a single entitlement.

### `            list           `

Lists the entitlements in a given project, folder, organization, and in a given location.

### `            patch           `

Updates the entitlement specified in the request.

### `            search           `

`SearchEntitlements` returns entitlements on which the caller has the specified access.
