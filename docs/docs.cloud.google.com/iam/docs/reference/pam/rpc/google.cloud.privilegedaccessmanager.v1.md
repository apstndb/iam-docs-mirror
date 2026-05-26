---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1
title: Package google.cloud.privilegedaccessmanager.v1
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

  - `  PrivilegedAccessManager  ` (interface)
  - `  AccessControlEntry  ` (message)
  - `  ApprovalWorkflow  ` (message)
  - `  ApproveGrantRequest  ` (message)
  - `  CheckOnboardingStatusRequest  ` (message)
  - `  CheckOnboardingStatusResponse  ` (message)
  - `  CheckOnboardingStatusResponse.Finding  ` (message)
  - `  CheckOnboardingStatusResponse.Finding.IAMAccessDenied  ` (message)
  - `  CreateEntitlementRequest  ` (message)
  - `  CreateGrantRequest  ` (message)
  - `  DeleteEntitlementRequest  ` (message)
  - `  DenyGrantRequest  ` (message)
  - `  Entitlement  ` (message)
  - `  Entitlement.AdditionalNotificationTargets  ` (message)
  - `  Entitlement.RequesterJustificationConfig  ` (message)
  - `  Entitlement.RequesterJustificationConfig.NotMandatory  ` (message)
  - `  Entitlement.RequesterJustificationConfig.Unstructured  ` (message)
  - `  Entitlement.State  ` (enum)
  - `  GetEntitlementRequest  ` (message)
  - `  GetGrantRequest  ` (message)
  - `  Grant  ` (message)
  - `  Grant.AuditTrail  ` (message)
  - `  Grant.State  ` (enum)
  - `  Grant.Timeline  ` (message)
  - `  Grant.Timeline.Event  ` (message)
  - `  Grant.Timeline.Event.Activated  ` (message)
  - `  Grant.Timeline.Event.ActivationFailed  ` (message)
  - `  Grant.Timeline.Event.Approved  ` (message)
  - `  Grant.Timeline.Event.Denied  ` (message)
  - `  Grant.Timeline.Event.Ended  ` (message)
  - `  Grant.Timeline.Event.Expired  ` (message)
  - `  Grant.Timeline.Event.ExternallyModified  ` (message)
  - `  Grant.Timeline.Event.Requested  ` (message)
  - `  Grant.Timeline.Event.Revoked  ` (message)
  - `  Grant.Timeline.Event.Scheduled  ` (message)
  - `  Grant.Timeline.Event.Withdrawn  ` (message)
  - `  Justification  ` (message)
  - `  ListEntitlementsRequest  ` (message)
  - `  ListEntitlementsResponse  ` (message)
  - `  ListGrantsRequest  ` (message)
  - `  ListGrantsResponse  ` (message)
  - `  ManualApprovals  ` (message)
  - `  ManualApprovals.Step  ` (message)
  - `  OperationMetadata  ` (message)
  - `  PrivilegedAccess  ` (message)
  - `  PrivilegedAccess.GcpIamAccess  ` (message)
  - `  PrivilegedAccess.GcpIamAccess.RoleBinding  ` (message)
  - `  RevokeGrantRequest  ` (message)
  - `  SearchEntitlementsRequest  ` (message)
  - `  SearchEntitlementsRequest.CallerAccessType  ` (enum)
  - `  SearchEntitlementsResponse  ` (message)
  - `  SearchGrantsRequest  ` (message)
  - `  SearchGrantsRequest.CallerRelationshipType  ` (enum)
  - `  SearchGrantsResponse  ` (message)
  - `  UpdateEntitlementRequest  ` (message)

## PrivilegedAccessManager

This API allows customers to manage temporary, request based privileged access to their resources.

It defines the following resource model:

  - A collection of `Entitlement` resources. An entitlement allows configuring (among other things):

  - Some kind of privileged access that users can request.

  - A set of users called *requesters* who can request this access.

  - A maximum duration for which the access can be requested.

  - An optional approval workflow which must be satisfied before access is granted.

  - A collection of `Grant` resources. A grant is a request by a requester to get the privileged access specified in an entitlement for some duration.

After the approval workflow as specified in the entitlement is satisfied, the specified access is given to the requester. The access is automatically taken back after the requested duration is over.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>ApproveGrant</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ApproveGrant(              ApproveGrantRequest            </code> ) returns ( <code dir="ltr" translate="no">             Grant            </code> )</p>
<p><code dir="ltr" translate="no">ApproveGrant</code> is used to approve a grant. This method can only be called on a grant when it's in the <code dir="ltr" translate="no">APPROVAL_AWAITED</code> state. This operation can't be undone.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CheckOnboardingStatus</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CheckOnboardingStatus(              CheckOnboardingStatusRequest            </code> ) returns ( <code dir="ltr" translate="no">             CheckOnboardingStatusResponse            </code> )</p>
<p><code dir="ltr" translate="no">CheckOnboardingStatus</code> reports the onboarding status for a project, folder, or organization. Any findings reported by this API need to be fixed before PAM can be used on the resource.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">parent</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.locations.checkOnboardingStatus</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreateEntitlement</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateEntitlement(              CreateEntitlementRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Creates a new entitlement in a given project, folder, organization, and in a given location.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">parent</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.entitlements.create</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreateGrant</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateGrant(              CreateGrantRequest            </code> ) returns ( <code dir="ltr" translate="no">             Grant            </code> )</p>
<p>Creates a grant in a given project, folder, or organization and location.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>DeleteEntitlement</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteEntitlement(              DeleteEntitlementRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes a single entitlement. This method can only be called when there are no in-progress ( <code dir="ltr" translate="no">ACTIVE</code> / <code dir="ltr" translate="no">ACTIVATING</code> / <code dir="ltr" translate="no">REVOKING</code> ) grants under the entitlement.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.entitlements.delete</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>DenyGrant</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DenyGrant(              DenyGrantRequest            </code> ) returns ( <code dir="ltr" translate="no">             Grant            </code> )</p>
<p><code dir="ltr" translate="no">DenyGrant</code> is used to deny a grant. This method can only be called on a grant when it's in the <code dir="ltr" translate="no">APPROVAL_AWAITED</code> state. This operation can't be undone.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>GetEntitlement</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetEntitlement(              GetEntitlementRequest            </code> ) returns ( <code dir="ltr" translate="no">             Entitlement            </code> )</p>
<p>Gets details of a single entitlement.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.entitlements.get</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>GetGrant</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetGrant(              GetGrantRequest            </code> ) returns ( <code dir="ltr" translate="no">             Grant            </code> )</p>
<p>Get details of a single grant.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.grants.get</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>ListEntitlements</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListEntitlements(              ListEntitlementsRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListEntitlementsResponse            </code> )</p>
<p>Lists the entitlements in a given project, folder, organization, and in a given location.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">parent</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.entitlements.list</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>ListGrants</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListGrants(              ListGrantsRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListGrantsResponse            </code> )</p>
<p>Lists grants for a given entitlement.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">parent</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.grants.list</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>RevokeGrant</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc RevokeGrant(              RevokeGrantRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p><code dir="ltr" translate="no">RevokeGrant</code> is used to immediately revoke access for a grant. This method can be called when the grant is in a non-terminal state.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.grants.revoke</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>SearchEntitlements</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc SearchEntitlements(              SearchEntitlementsRequest            </code> ) returns ( <code dir="ltr" translate="no">             SearchEntitlementsResponse            </code> )</p>
<p><code dir="ltr" translate="no">SearchEntitlements</code> returns entitlements on which the caller has the specified access.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>SearchGrants</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc SearchGrants(              SearchGrantsRequest            </code> ) returns ( <code dir="ltr" translate="no">             SearchGrantsResponse            </code> )</p>
<p><code dir="ltr" translate="no">SearchGrants</code> returns grants that are related to the calling user in the specified way.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UpdateEntitlement</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateEntitlement(              UpdateEntitlementRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Updates the entitlement specified in the request. Updated fields in the entitlement need to be specified in an update mask. The changes made to an entitlement are applicable only on future grants of the entitlement. However, if new approvers are added or existing approvers are removed from the approval workflow, the changes are effective on existing grants.</p>
<p>The following fields are not supported for updates:</p>
<ul>
<li>All immutable fields</li>
<li>Entitlement name</li>
<li>Resource name</li>
<li>Resource type</li>
<li>Adding an approval workflow in an entitlement which previously had no approval workflow.</li>
<li>Deleting the approval workflow from an entitlement.</li>
<li>Adding or deleting a step in the approval workflow (only one step is supported)</li>
</ul>
<p>Note that updates are allowed on the list of approvers in an approval workflow step.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.entitlements.update</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

## AccessControlEntry

`AccessControlEntry` is used to control who can do some operation.

Fields

`principals[]`

`string`

Optional. Users who are allowed for the operation. Each entry should be a valid v1 IAM principal identifier. The format for these is documented at: <https://cloud.google.com/iam/docs/principal-identifiers#v1>

## ApprovalWorkflow

Different types of approval workflows that can be used to gate privileged access granting.

Fields

Union field `approval_workflow` .

`approval_workflow` can be only one of the following:

`manual_approvals`

`  ManualApprovals  `

An approval workflow where users designated as approvers review and act on the grants.

## ApproveGrantRequest

Request message for `ApproveGrant` method.

Fields

`name`

`string`

Required. Name of the grant resource which is being approved.

`reason`

`string`

Optional. The reason for approving this grant. This is required if the `require_approver_justification` field of the `ManualApprovals` workflow used in this grant is true.

## CheckOnboardingStatusRequest

Request message for `CheckOnboardingStatus` method.

Fields

`parent`

`string`

Required. The resource for which the onboarding status should be checked. Should be in one of the following formats:

  - `projects/{project-number|project-id}/locations/{region}`
  - `folders/{folder-number}/locations/{region}`
  - `organizations/{organization-number}/locations/{region}`

## CheckOnboardingStatusResponse

Response message for `CheckOnboardingStatus` method.

Fields

`service_account`

`string`

The service account that PAM uses to act on this resource.

`findings[]`

`  Finding  `

List of issues that are preventing PAM from functioning for this resource and need to be fixed to complete onboarding. Some issues might not be detected or reported.

## Finding

Finding represents an issue which prevents PAM from functioning properly for this resource.

Fields

Union field `finding_type` .

`finding_type` can be only one of the following:

`iam_access_denied`

`  IAMAccessDenied  `

PAM's service account is being denied access by Cloud IAM.

## IAMAccessDenied

PAM's service account is being denied access by Cloud IAM. This can be fixed by granting a role that contains the missing permissions to the service account or exempting it from deny policies if they are blocking the access.

Fields

`missing_permissions[]`

`string`

List of permissions that are being denied.

## CreateEntitlementRequest

Message for creating an entitlement.

Fields

`parent`

`string`

Required. Name of the parent resource for the entitlement. Possible formats:

  - `organizations/{organization-number}/locations/{region}`
  - `folders/{folder-number}/locations/{region}`
  - `projects/{project-id|project-number}/locations/{region}`

`entitlement_id`

`string`

Required. The ID to use for this entitlement. This becomes the last part of the resource name.

This value should be 4-63 characters in length, and valid characters are "\[a-z\]", "\[0-9\]", and "-". The first character should be from \[a-z\].

This value should be unique among all other entitlements under the specified `parent` .

`entitlement`

`  Entitlement  `

Required. The resource being created

`request_id`

`string`

Optional. An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server knows to ignore the request if it has already been completed. The server guarantees this for at least 60 minutes after the first request.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, ignores the second request and returns the previous operation's response. This prevents clients from accidentally creating duplicate entitlements.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).

## CreateGrantRequest

Message for creating a grant

Fields

`parent`

`string`

Required. Name of the parent entitlement for which this grant is being requested.

`grant`

`  Grant  `

Required. The resource being created.

`request_id`

`string`

Optional. An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server knows to ignore the request if it has already been completed. The server guarantees this for at least 60 minutes after the first request.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, ignores the second request. This prevents clients from accidentally creating duplicate grants.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).

## DeleteEntitlementRequest

Message for deleting an entitlement.

Fields

`name`

`string`

Required. Name of the resource.

`request_id`

`string`

Optional. An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server knows to ignore the request if it has already been completed. The server guarantees this for at least 60 minutes after the first request.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, ignores the second request.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).

`force`

`bool`

Optional. If set to true, any child grant under this entitlement is also deleted. (Otherwise, the request only works if the entitlement has no child grant.)

## DenyGrantRequest

Request message for `DenyGrant` method.

Fields

`name`

`string`

Required. Name of the grant resource which is being denied.

`reason`

`string`

Optional. The reason for denying this grant. This is required if `require_approver_justification` field of the `ManualApprovals` workflow used in this grant is true.

## Entitlement

An entitlement defines the eligibility of a set of users to obtain predefined access for some time possibly after going through an approval workflow.

Fields

`name`

`string`

Identifier. Name of the entitlement. Possible formats:

  - `organizations/{organization-number}/locations/{region}/entitlements/{entitlement-id}`
  - `folders/{folder-number}/locations/{region}/entitlements/{entitlement-id}`
  - `projects/{project-id|project-number}/locations/{region}/entitlements/{entitlement-id}`

`create_time`

`  Timestamp  `

Output only. Create time stamp.

`update_time`

`  Timestamp  `

Output only. Update time stamp.

`eligible_users[]`

`  AccessControlEntry  `

Optional. Who can create grants using this entitlement. This list should contain at most one entry.

`approval_workflow`

`  ApprovalWorkflow  `

Optional. The approvals needed before access are granted to a requester. No approvals are needed if this field is null.

`privileged_access`

`  PrivilegedAccess  `

Required. The access granted to a requester on successful approval.

`max_request_duration`

`  Duration  `

Required. The maximum amount of time that access is granted for a request. A requester can ask for a shorter duration but never a longer one. The supported range is between 30 minutes and 168 hours (7 days).

`state`

`  State  `

Output only. Current state of this entitlement.

`requester_justification_config`

`  RequesterJustificationConfig  `

Required. The manner in which the requester should provide a justification for requesting access.

`additional_notification_targets`

`  AdditionalNotificationTargets  `

Optional. Additional email addresses to be notified based on actions taken.

`etag`

`string`

An `etag` is used for optimistic concurrency control as a way to prevent simultaneous updates to the same entitlement. An `etag` is returned in the response to `GetEntitlement` and the caller should put the `etag` in the request to `UpdateEntitlement` so that their change is applied on the same version. If this field is omitted or if there is a mismatch while updating an entitlement, then the server rejects the request.

## AdditionalNotificationTargets

`AdditionalNotificationTargets` includes email addresses to be notified.

Fields

`admin_email_recipients[]`

`string`

Optional. Additional email addresses to be notified when a principal (requester) is granted access.

`requester_email_recipients[]`

`string`

Optional. Additional email address to be notified about an eligible entitlement.

## RequesterJustificationConfig

Defines how a requester must provide a justification when requesting access.

Fields

Union field `justification_type` . This is a required field and the user must explicitly opt out if a justification from the requester isn't mandatory. `justification_type` can be only one of the following:

`not_mandatory`

`  NotMandatory  `

This option means the requester isn't required to provide a justification.

`unstructured`

`  Unstructured  `

This option means the requester must provide a string as justification. If this is selected, the server allows the requester to provide a justification but doesn't validate it.

## NotMandatory

This type has no fields.

The justification is not mandatory but can be provided in any of the supported formats.

## Unstructured

This type has no fields.

The requester has to provide a justification in the form of a string.

## State

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

## GetEntitlementRequest

Message for getting an entitlement.

Fields

`name`

`string`

Required. Name of the resource.

## GetGrantRequest

Message for getting a grant.

Fields

`name`

`string`

Required. Name of the resource.

## Grant

A grant represents a request from a user for obtaining the access specified in an entitlement they are eligible for.

Fields

`name`

`string`

Identifier. Name of this grant. Possible formats:

  - `organizations/{organization-number}/locations/{region}/entitlements/{entitlement-id}/grants/{grant-id}`
  - `folders/{folder-number}/locations/{region}/entitlements/{entitlement-id}/grants/{grant-id}`
  - `projects/{project-id|project-number}/locations/{region}/entitlements/{entitlement-id}/grants/{grant-id}`

The last segment of this name ( `{grant-id}` ) is autogenerated.

`create_time`

`  Timestamp  `

Output only. Create time stamp.

`update_time`

`  Timestamp  `

Output only. Update time stamp.

`requester`

`string`

Output only. Username of the user who created this grant.

`requested_duration`

`  Duration  `

Required. The amount of time access is needed for. This value should be shorter than the `max_request_duration` value of the entitlement.

`justification`

`  Justification  `

Optional. Justification of why this access is needed.

`state`

`  State  `

Output only. Current state of this grant.

`timeline`

`  Timeline  `

Output only. Timeline of this grant.

`privileged_access`

`  PrivilegedAccess  `

Output only. The access that would be granted by this grant.

`audit_trail`

`  AuditTrail  `

Output only. Audit trail of access provided by this grant. If unspecified then access was never granted.

`additional_email_recipients[]`

`string`

Optional. Additional email addresses to notify for all the actions performed on the grant.

`externally_modified`

`bool`

Output only. Flag set by the PAM system to indicate that policy bindings made by this grant have been modified from outside PAM.

After it is set, this flag remains set forever irrespective of the grant state. A `true` value here indicates that PAM no longer has any certainty on the access a user has because of this grant.

## AuditTrail

Audit trail for the access provided by this grant.

Fields

`access_grant_time`

`  Timestamp  `

Output only. The time at which access was given.

`access_remove_time`

`  Timestamp  `

Output only. The time at which the system removed access. This could be because of an automatic expiry or because of a revocation.

If unspecified, then access hasn't been removed yet.

## State

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

## Timeline

Timeline of a grant describing what happened to it and when.

Fields

`events[]`

`  Event  `

Output only. The events that have occurred on this grant. This list contains entries in the same order as they occurred. The first entry is always be of type `Requested` and there is always at least one entry in this array.

## Event

A single operation on the grant.

Fields

`event_time`

`  Timestamp  `

Output only. The time (as recorded at server) when this event occurred.

Union field `event` .

`event` can be only one of the following:

`requested`

`  Requested  `

The grant was requested.

`approved`

`  Approved  `

The grant was approved.

`denied`

`  Denied  `

The grant was denied.

`revoked`

`  Revoked  `

The grant was revoked.

`scheduled`

`  Scheduled  `

The grant has been scheduled to give access.

`activated`

`  Activated  `

The grant was successfully activated to give access.

`activation_failed`

`  ActivationFailed  `

There was a non-retriable error while trying to give access.

`expired`

`  Expired  `

The approval workflow did not complete in the necessary duration, and so the grant is expired.

`ended`

`  Ended  `

Access given by the grant ended automatically as the approved duration was over.

`externally_modified`

`  ExternallyModified  `

The policy bindings made by grant have been modified outside of PAM.

`withdrawn`

`  Withdrawn  `

The grant was withdrawn.

## Activated

This type has no fields.

An event representing that the grant was successfully activated.

## ActivationFailed

An event representing that the grant activation failed.

Fields

`error`

`  Status  `

Output only. The error that occurred while activating the grant.

## Approved

An event representing that the grant was approved.

Fields

`reason`

`string`

Output only. The reason provided by the approver for approving the grant.

`actor`

`string`

Output only. Username of the user who approved the grant.

## Denied

An event representing that the grant was denied.

Fields

`reason`

`string`

Output only. The reason provided by the approver for denying the grant.

`actor`

`string`

Output only. Username of the user who denied the grant.

## Ended

This type has no fields.

An event representing that the grant has ended.

## Expired

This type has no fields.

An event representing that the grant was expired.

## ExternallyModified

This type has no fields.

An event representing that the policy bindings made by this grant were modified externally.

## Requested

An event representing that a grant was requested.

Fields

`expire_time`

`  Timestamp  `

Output only. The time at which this grant expires unless the approval workflow completes. If omitted, then the request never expires.

## Revoked

An event representing that the grant was revoked.

Fields

`reason`

`string`

Output only. The reason provided by the user for revoking the grant.

`actor`

`string`

Output only. Username of the user who revoked the grant.

## Scheduled

An event representing that the grant has been scheduled to be activated later.

Fields

`scheduled_activation_time`

`  Timestamp  `

Output only. The time at which the access is granted.

## Withdrawn

This type has no fields.

An event representing that the grant was withdrawn.

## Justification

Justification represents a justification for requesting access.

Fields

Union field `justification` .

`justification` can be only one of the following:

`unstructured_justification`

`string`

A free form textual justification. The system only ensures that this is not empty. No other kind of validation is performed on the string.

## ListEntitlementsRequest

Message for requesting list of entitlements.

Fields

`parent`

`string`

Required. The parent which owns the entitlement resources.

`page_size`

`int32`

Optional. Requested page size. Server may return fewer items than requested. If unspecified, the server picks an appropriate default.

`page_token`

`string`

Optional. A token identifying a page of results the server should return.

`filter`

`string`

Optional. Filtering results.

`order_by`

`string`

Optional. Hint for how to order the results.

## ListEntitlementsResponse

Message for response to listing entitlements.

Fields

`entitlements[]`

`  Entitlement  `

The list of entitlements.

`next_page_token`

`string`

A token identifying a page of results the server should return.

`unreachable[]`

`string`

Locations that could not be reached.

## ListGrantsRequest

Message for requesting list of grants.

Fields

`parent`

`string`

Required. The parent resource which owns the grants.

`page_size`

`int32`

Optional. Requested page size. The server may return fewer items than requested. If unspecified, the server picks an appropriate default.

`page_token`

`string`

Optional. A token identifying a page of results the server should return.

`filter`

`string`

Optional. Filtering results.

`order_by`

`string`

Optional. Hint for how to order the results

## ListGrantsResponse

Message for response to listing grants.

Fields

`grants[]`

`  Grant  `

The list of grants.

`next_page_token`

`string`

A token identifying a page of results the server should return.

`unreachable[]`

`string`

Locations that could not be reached.

## ManualApprovals

A manual approval workflow where users who are designated as approvers need to call the `ApproveGrant` / `DenyGrant` APIs for a grant. The workflow can consist of multiple serial steps where each step defines who can act as approver in that step and how many of those users should approve before the workflow moves to the next step.

This can be used to create approval workflows such as:

  - Require an approval from any user in a group G.
  - Require an approval from any k number of users from a Group G.
  - Require an approval from any user in a group G and then from a user U.

A single user might be part of the `approvers` ACL for multiple steps in this workflow, but they can only approve once and that approval is only considered to satisfy the approval step at which it was granted.

Fields

`require_approver_justification`

`bool`

Optional. Do the approvers need to provide a justification for their actions?

`steps[]`

`  Step  `

Optional. List of approval steps in this workflow. These steps are followed in the specified order sequentially. Only 1 step is supported.

## Step

Step represents a logical step in a manual approval workflow.

Fields

`approvers[]`

`  AccessControlEntry  `

Optional. The potential set of approvers in this step. This list must contain at most one entry.

`approvals_needed`

`int32`

Required. How many users from the above list need to approve. If there aren't enough distinct users in the list, then the workflow indefinitely blocks. Should always be greater than 0. 1 is the only supported value.

`approver_email_recipients[]`

`string`

Optional. Additional email addresses to be notified when a grant is pending approval.

## OperationMetadata

Represents the metadata of the long-running operation.

Fields

`create_time`

`  Timestamp  `

Output only. The time the operation was created.

`end_time`

`  Timestamp  `

Output only. The time the operation finished running.

`target`

`string`

Output only. Server-defined resource path for the target of the operation.

`verb`

`string`

Output only. Name of the verb executed by the operation.

`status_message`

`string`

Output only. Human-readable status of the operation, if any.

`requested_cancellation`

`bool`

Output only. Identifies whether the user has requested cancellation of the operation. Operations that have been cancelled successfully have \[Operation.error\]\[\] value with a `  google.rpc.Status.code  ` of 1, corresponding to `Code.CANCELLED` .

`api_version`

`string`

Output only. API version used to start the operation.

## PrivilegedAccess

Privileged access that this service can be used to gate.

Fields

Union field `access_type` .

`access_type` can be only one of the following:

`gcp_iam_access`

`  GcpIamAccess  `

Access to a Google Cloud resource through IAM.

## GcpIamAccess

`GcpIamAccess` represents IAM based access control on a Google Cloud resource. Refer to <https://cloud.google.com/iam/docs> to understand more about IAM.

Fields

`resource_type`

`string`

Required. The type of this resource.

`resource`

`string`

Required. Name of the resource.

`role_bindings[]`

`  RoleBinding  `

Required. Role bindings that are created on successful grant.

## RoleBinding

IAM role bindings that are created after a successful grant.

Fields

`role`

`string`

Required. IAM role to be granted. <https://cloud.google.com/iam/docs/roles-overview> .

`condition_expression`

`string`

Optional. The expression field of the IAM condition to be associated with the role. If specified, a user with an active grant for this entitlement is able to access the resource only if this condition evaluates to true for their request.

This field uses the same CEL format as IAM and supports all attributes that IAM supports, except tags. <https://cloud.google.com/iam/docs/conditions-overview#attributes> .

## RevokeGrantRequest

Request message for `RevokeGrant` method.

Fields

`name`

`string`

Required. Name of the grant resource which is being revoked.

`reason`

`string`

Optional. The reason for revoking this grant.

## SearchEntitlementsRequest

Request message for `SearchEntitlements` method.

Fields

`parent`

`string`

Required. The parent which owns the entitlement resources.

`caller_access_type`

`  CallerAccessType  `

Required. Only entitlements where the calling user has this access are returned.

`filter`

`string`

Optional. Only entitlements matching this filter are returned in the response.

`page_size`

`int32`

Optional. Requested page size. The server may return fewer items than requested. If unspecified, the server picks an appropriate default.

`page_token`

`string`

Optional. A token identifying a page of results the server should return.

## CallerAccessType

Different types of access a user can have on the entitlement resource.

Enums

`CALLER_ACCESS_TYPE_UNSPECIFIED`

Unspecified access type.

`GRANT_REQUESTER`

The user has access to create grants using this entitlement.

`GRANT_APPROVER`

The user has access to approve/deny grants created under this entitlement.

## SearchEntitlementsResponse

Response message for `SearchEntitlements` method.

Fields

`entitlements[]`

`  Entitlement  `

The list of entitlements.

`next_page_token`

`string`

A token identifying a page of results the server should return.

## SearchGrantsRequest

Request message for `SearchGrants` method.

Fields

`parent`

`string`

Required. The parent which owns the grant resources.

`caller_relationship`

`  CallerRelationshipType  `

Required. Only grants which the caller is related to by this relationship are returned in the response.

`filter`

`string`

Optional. Only grants matching this filter are returned in the response.

`page_size`

`int32`

Optional. Requested page size. The server may return fewer items than requested. If unspecified, server picks an appropriate default.

`page_token`

`string`

Optional. A token identifying a page of results the server should return.

## CallerRelationshipType

Different types of relationships a user can have with a grant.

Enums

`CALLER_RELATIONSHIP_TYPE_UNSPECIFIED`

Unspecified caller relationship type.

`HAD_CREATED`

The user created this grant by calling `CreateGrant` earlier.

`CAN_APPROVE`

The user is an approver for the entitlement that this grant is parented under and can currently approve/deny it.

`HAD_APPROVED`

The caller had successfully approved/denied this grant earlier.

## SearchGrantsResponse

Response message for `SearchGrants` method.

Fields

`grants[]`

`  Grant  `

The list of grants.

`next_page_token`

`string`

A token identifying a page of results the server should return.

## UpdateEntitlementRequest

Message for updating an entitlement.

Fields

`entitlement`

`  Entitlement  `

Required. The entitlement resource that is updated.

`update_mask`

`  FieldMask  `

Required. The list of fields to update. A field is overwritten if, and only if, it is in the mask. Any immutable fields set in the mask are ignored by the server. Repeated fields and map fields are only allowed in the last position of a `paths` string and overwrite the existing values. Hence an update to a repeated field or a map should contain the entire list of values. The fields specified in the update\_mask are relative to the resource and not to the request. (e.g. `MaxRequestDuration` ; *not* `entitlement.MaxRequestDuration` ) A value of '\*' for this field refers to full replacement of the resource.
