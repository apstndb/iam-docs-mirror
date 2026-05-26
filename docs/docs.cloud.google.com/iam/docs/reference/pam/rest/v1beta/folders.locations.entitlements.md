---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements
title: 'REST Resource: folders.locations.entitlements'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: Entitlement](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.SCHEMA_REPRESENTATION)
      - [AccessControlEntry](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.AccessControlEntry)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.AccessControlEntry.SCHEMA_REPRESENTATION)
      - [ApprovalWorkflow](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.ApprovalWorkflow)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.ApprovalWorkflow.SCHEMA_REPRESENTATION)
      - [ManualApprovals](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.ManualApprovals)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.ManualApprovals.SCHEMA_REPRESENTATION)
      - [Step](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.Step)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.Step.SCHEMA_REPRESENTATION)
      - [State](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.State)
      - [RequesterJustificationConfig](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.RequesterJustificationConfig)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.RequesterJustificationConfig.SCHEMA_REPRESENTATION)
      - [NotMandatory](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.NotMandatory)
      - [Unstructured](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.Unstructured)
      - [AdditionalNotificationTargets](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.AdditionalNotificationTargets)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.AdditionalNotificationTargets.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#METHODS_SUMMARY)

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

### AccessControlEntry

`AccessControlEntry` is used to control who can do some operation.

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
  &quot;principals&quot;: [
    string
  ]
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`principals[]`

`string`

Optional. Users who are allowed for the operation. Each entry should be a valid v1 IAM principal identifier. The format for these is documented at: <https://cloud.google.com/iam/docs/principal-identifiers#v1>

### ApprovalWorkflow

Different types of approval workflows that can be used to gate privileged access granting.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field approval_workflow can be only one of the following:&quot;manualApprovals&quot;: {object (ManualApprovals)}// End of list of possible types for union field approval_workflow.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `approval_workflow` .

`approval_workflow` can be only one of the following:

`manualApprovals`

` object ( ManualApprovals  ` )

An approval workflow where users designated as approvers review and act on the grants.

### ManualApprovals

A manual approval workflow where users who are designated as approvers need to call the `ApproveGrant` / `DenyGrant` APIs for a grant. The workflow can consist of multiple serial steps where each step defines who can act as approver in that step and how many of those users should approve before the workflow moves to the next step.

This can be used to create approval workflows such as:

  - Require an approval from any user in a group G.
  - Require an approval from any k number of users from a Group G.
  - Require an approval from any user in a group G and then from a user U.

A single user might be part of the `approvers` ACL for multiple steps in this workflow, but they can only approve once and that approval is only considered to satisfy the approval step at which it was granted.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;requireApproverJustification&quot;: boolean,&quot;steps&quot;: [{object (Step)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`requireApproverJustification`

`boolean`

Optional. Do the approvers need to provide a justification for their actions?

`steps[]`

` object ( Step  ` )

Optional. List of approval steps in this workflow. These steps are followed in the specified order sequentially. Only 1 step is supported.

### Step

Step represents a logical step in a manual approval workflow.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;approvers&quot;: [{object (AccessControlEntry)}],&quot;approvalsNeeded&quot;: integer,&quot;approverEmailRecipients&quot;: [string],&quot;id&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`approvers[]`

` object ( AccessControlEntry  ` )

Optional. The potential set of approvers in this step. This list must contain at most one entry.

`approvalsNeeded`

`integer`

Required. How many users from the above list need to approve. If there aren't enough distinct users in the list, then the workflow indefinitely blocks. Should always be greater than 0. 1 is the only supported value.

`approverEmailRecipients[]`

`string`

Optional. Additional email addresses to be notified when a grant is pending approval.

`id`

`string`

Output only. Step ID used to identify the step in the workflow.

### State

Different states an entitlement can be in.

Enums

`STATE_UNSPECIFIED`

Unspecified state. This value is never returned by the server.

`CREATING`

The entitlement is being created.

`AVAILABLE`

The entitlement is available for requesting access.

`DELETING`

The entitlement is being deleted.

`DELETED`

The entitlement has been deleted.

`UPDATING`

The entitlement is being updated.

### RequesterJustificationConfig

Defines how a requester must provide a justification when requesting access.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field justification_type can be only one of the following:&quot;notMandatory&quot;: {object (NotMandatory)},&quot;unstructured&quot;: {object (Unstructured)}// End of list of possible types for union field justification_type.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `justification_type` . This is a required field and the user must explicitly opt out if a justification from the requester isn't mandatory. `justification_type` can be only one of the following:

`notMandatory`

` object ( NotMandatory  ` )

This option means the requester isn't required to provide a justification.

`unstructured`

` object ( Unstructured  ` )

This option means the requester must provide a string as justification. If this is selected, the server allows the requester to provide a justification but doesn't validate it.

### NotMandatory

This type has no fields.

The justification is not mandatory but can be provided in any of the supported formats.

### Unstructured

This type has no fields.

The requester has to provide a justification in the form of a string.

### AdditionalNotificationTargets

`AdditionalNotificationTargets` includes email addresses to be notified.

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
  &quot;adminEmailRecipients&quot;: [
    string
  ],
  &quot;requesterEmailRecipients&quot;: [
    string
  ]
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`adminEmailRecipients[]`

`string`

Optional. Additional email addresses to be notified when a principal (requester) is granted access.

`requesterEmailRecipients[]`

`string`

Optional. Additional email address to be notified about an eligible entitlement.

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
