---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1
title: Package google.cloud.privilegedaccessmanager.v1
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

- [`PrivilegedAccessManager`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager) (interface)
- [`AccessControlEntry`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.AccessControlEntry) (message)
- [`ApprovalWorkflow`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ApprovalWorkflow) (message)
- [`ApproveGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ApproveGrantRequest) (message)
- [`CheckOnboardingStatusRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.CheckOnboardingStatusRequest) (message)
- [`CheckOnboardingStatusResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.CheckOnboardingStatusResponse) (message)
- [`CheckOnboardingStatusResponse.Finding`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.CheckOnboardingStatusResponse.Finding) (message)
- [`CheckOnboardingStatusResponse.Finding.IAMAccessDenied`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.CheckOnboardingStatusResponse.Finding.IAMAccessDenied) (message)
- [`CreateEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.CreateEntitlementRequest) (message)
- [`CreateGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.CreateGrantRequest) (message)
- [`DeleteEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.DeleteEntitlementRequest) (message)
- [`DenyGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.DenyGrantRequest) (message)
- [`Entitlement`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement) (message)
- [`Entitlement.AdditionalNotificationTargets`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement.AdditionalNotificationTargets) (message)
- [`Entitlement.RequesterJustificationConfig`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement.RequesterJustificationConfig) (message)
- [`Entitlement.RequesterJustificationConfig.NotMandatory`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement.RequesterJustificationConfig.NotMandatory) (message)
- [`Entitlement.RequesterJustificationConfig.Unstructured`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement.RequesterJustificationConfig.Unstructured) (message)
- [`Entitlement.State`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement.State) (enum)
- [`GetEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.GetEntitlementRequest) (message)
- [`GetGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.GetGrantRequest) (message)
- [`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant) (message)
- [`Grant.AuditTrail`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.AuditTrail) (message)
- [`Grant.State`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.State) (enum)
- [`Grant.Timeline`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline) (message)
- [`Grant.Timeline.Event`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event) (message)
- [`Grant.Timeline.Event.Activated`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Activated) (message)
- [`Grant.Timeline.Event.ActivationFailed`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.ActivationFailed) (message)
- [`Grant.Timeline.Event.Approved`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Approved) (message)
- [`Grant.Timeline.Event.Denied`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Denied) (message)
- [`Grant.Timeline.Event.Ended`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Ended) (message)
- [`Grant.Timeline.Event.Expired`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Expired) (message)
- [`Grant.Timeline.Event.ExternallyModified`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.ExternallyModified) (message)
- [`Grant.Timeline.Event.Requested`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Requested) (message)
- [`Grant.Timeline.Event.Revoked`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Revoked) (message)
- [`Grant.Timeline.Event.Scheduled`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Scheduled) (message)
- [`Grant.Timeline.Event.Withdrawn`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Withdrawn) (message)
- [`Justification`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Justification) (message)
- [`ListEntitlementsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ListEntitlementsRequest) (message)
- [`ListEntitlementsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ListEntitlementsResponse) (message)
- [`ListGrantsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ListGrantsRequest) (message)
- [`ListGrantsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ListGrantsResponse) (message)
- [`ManualApprovals`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ManualApprovals) (message)
- [`ManualApprovals.Step`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ManualApprovals.Step) (message)
- [`OperationMetadata`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.OperationMetadata) (message)
- [`PrivilegedAccess`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.PrivilegedAccess) (message)
- [`PrivilegedAccess.GcpIamAccess`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.PrivilegedAccess.GcpIamAccess) (message)
- [`PrivilegedAccess.GcpIamAccess.RoleBinding`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.PrivilegedAccess.GcpIamAccess.RoleBinding) (message)
- [`RevokeGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.RevokeGrantRequest) (message)
- [`SearchEntitlementsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.SearchEntitlementsRequest) (message)
- [`SearchEntitlementsRequest.CallerAccessType`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.SearchEntitlementsRequest.CallerAccessType) (enum)
- [`SearchEntitlementsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.SearchEntitlementsResponse) (message)
- [`SearchGrantsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.SearchGrantsRequest) (message)
- [`SearchGrantsRequest.CallerRelationshipType`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.SearchGrantsRequest.CallerRelationshipType) (enum)
- [`SearchGrantsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.SearchGrantsResponse) (message)
- [`UpdateEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.UpdateEntitlementRequest) (message)

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

**ApproveGrant**

`rpc ApproveGrant( `[`ApproveGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ApproveGrantRequest)` ) returns ( `[`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant)` )`

`ApproveGrant` is used to approve a grant. This method can only be called on a grant when it's in the `APPROVAL_AWAITED` state. This operation can't be undone.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**CheckOnboardingStatus**

`rpc CheckOnboardingStatus( `[`CheckOnboardingStatusRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.CheckOnboardingStatusRequest)` ) returns ( `[`CheckOnboardingStatusResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.CheckOnboardingStatusResponse)` )`

`CheckOnboardingStatus` reports the onboarding status for a project, folder, or organization. Any findings reported by this API need to be fixed before PAM can be used on the resource.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `privilegedaccessmanager.locations.checkOnboardingStatus`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**CreateEntitlement**

`rpc CreateEntitlement( `[`CreateEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.CreateEntitlementRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.longrunning#google.longrunning.Operation)` )`

Creates a new entitlement in a given project, folder, organization, and in a given location.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `privilegedaccessmanager.entitlements.create`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**CreateGrant**

`rpc CreateGrant( `[`CreateGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.CreateGrantRequest)` ) returns ( `[`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant)` )`

Creates a grant in a given project, folder, or organization and location.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**DeleteEntitlement**

`rpc DeleteEntitlement( `[`DeleteEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.DeleteEntitlementRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.longrunning#google.longrunning.Operation)` )`

Deletes a single entitlement. This method can only be called when there are no in-progress ( `ACTIVE` / `ACTIVATING` / `REVOKING` ) grants under the entitlement.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `privilegedaccessmanager.entitlements.delete`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**DenyGrant**

`rpc DenyGrant( `[`DenyGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.DenyGrantRequest)` ) returns ( `[`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant)` )`

`DenyGrant` is used to deny a grant. This method can only be called on a grant when it's in the `APPROVAL_AWAITED` state. This operation can't be undone.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**GetEntitlement**

`rpc GetEntitlement( `[`GetEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.GetEntitlementRequest)` ) returns ( `[`Entitlement`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement)` )`

Gets details of a single entitlement.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `privilegedaccessmanager.entitlements.get`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**GetGrant**

`rpc GetGrant( `[`GetGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.GetGrantRequest)` ) returns ( `[`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant)` )`

Get details of a single grant.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `privilegedaccessmanager.grants.get`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**ListEntitlements**

`rpc ListEntitlements( `[`ListEntitlementsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ListEntitlementsRequest)` ) returns ( `[`ListEntitlementsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ListEntitlementsResponse)` )`

Lists the entitlements in a given project, folder, organization, and in a given location.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `privilegedaccessmanager.entitlements.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**ListGrants**

`rpc ListGrants( `[`ListGrantsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ListGrantsRequest)` ) returns ( `[`ListGrantsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ListGrantsResponse)` )`

Lists grants for a given entitlement.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `privilegedaccessmanager.grants.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**RevokeGrant**

`rpc RevokeGrant( `[`RevokeGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.RevokeGrantRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.longrunning#google.longrunning.Operation)` )`

`RevokeGrant` is used to immediately revoke access for a grant. This method can be called when the grant is in a non-terminal state.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `privilegedaccessmanager.grants.revoke`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**SearchEntitlements**

`rpc SearchEntitlements( `[`SearchEntitlementsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.SearchEntitlementsRequest)` ) returns ( `[`SearchEntitlementsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.SearchEntitlementsResponse)` )`

`SearchEntitlements` returns entitlements on which the caller has the specified access.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**SearchGrants**

`rpc SearchGrants( `[`SearchGrantsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.SearchGrantsRequest)` ) returns ( `[`SearchGrantsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.SearchGrantsResponse)` )`

`SearchGrants` returns grants that are related to the calling user in the specified way.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**UpdateEntitlement**

`rpc UpdateEntitlement( `[`UpdateEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.UpdateEntitlementRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.longrunning#google.longrunning.Operation)` )`

Updates the entitlement specified in the request. Updated fields in the entitlement need to be specified in an update mask. The changes made to an entitlement are applicable only on future grants of the entitlement. However, if new approvers are added or existing approvers are removed from the approval workflow, the changes are effective on existing grants.

The following fields are not supported for updates:

- All immutable fields
- Entitlement name
- Resource name
- Resource type
- Adding an approval workflow in an entitlement which previously had no approval workflow.
- Deleting the approval workflow from an entitlement.
- Adding or deleting a step in the approval workflow (only one step is supported)

Note that updates are allowed on the list of approvers in an approval workflow step.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `privilegedaccessmanager.entitlements.update`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

## AccessControlEntry

`AccessControlEntry` is used to control who can do some operation.

| Fields         |                                                                                                                                                                                                                           |
|----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `principals[]` | `string` Optional. Users who are allowed for the operation. Each entry should be a valid v1 IAM principal identifier. The format for these is documented at: <https://cloud.google.com/iam/docs/principal-identifiers#v1> |

## ApprovalWorkflow

Different types of approval workflows that can be used to gate privileged access granting.

| Fields                                                                                  |                                                                                                                                                                                                                                                                      |
|-----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `approval_workflow` . `approval_workflow` can be only one of the following: |                                                                                                                                                                                                                                                                      |
| `manual_approvals`                                                                      | [`ManualApprovals`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ManualApprovals) An approval workflow where users designated as approvers review and act on the grants. |

## ApproveGrantRequest

Request message for `ApproveGrant` method.

| Fields   |                                                                                                                                                                                      |
|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`   | `string` Required. Name of the grant resource which is being approved.                                                                                                               |
| `reason` | `string` Optional. The reason for approving this grant. This is required if the `require_approver_justification` field of the `ManualApprovals` workflow used in this grant is true. |

## CheckOnboardingStatusRequest

Request message for `CheckOnboardingStatus` method.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>parent</code></td>
<td><p><code>string</code></p>
<p>Required. The resource for which the onboarding status should be checked. Should be in one of the following formats:</p>
<ul>
<li><code>projects/{project-number|project-id}/locations/{region}</code></li>
<li><code>folders/{folder-number}/locations/{region}</code></li>
<li><code>organizations/{organization-number}/locations/{region}</code></li>
</ul></td>
</tr>
</tbody>
</table>

## CheckOnboardingStatusResponse

Response message for `CheckOnboardingStatus` method.

| Fields            |                                                                                                                                                                                                                                                                                                                                                                   |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `service_account` | `string` The service account that PAM uses to act on this resource.                                                                                                                                                                                                                                                                                               |
| `findings[]`      | [`Finding`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.CheckOnboardingStatusResponse.Finding) List of issues that are preventing PAM from functioning for this resource and need to be fixed to complete onboarding. Some issues might not be detected or reported. |

## Finding

Finding represents an issue which prevents PAM from functioning properly for this resource.

| Fields                                                                        |                                                                                                                                                                                                                                                                                |
|-------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `finding_type` . `finding_type` can be only one of the following: |                                                                                                                                                                                                                                                                                |
| `iam_access_denied`                                                           | [`IAMAccessDenied`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.CheckOnboardingStatusResponse.Finding.IAMAccessDenied) PAM's service account is being denied access by Cloud IAM. |

## IAMAccessDenied

PAM's service account is being denied access by Cloud IAM. This can be fixed by granting a role that contains the missing permissions to the service account or exempting it from deny policies if they are blocking the access.

| Fields                  |                                                     |
|-------------------------|-----------------------------------------------------|
| `missing_permissions[]` | `string` List of permissions that are being denied. |

## CreateEntitlementRequest

Message for creating an entitlement.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>parent</code></td>
<td><p><code>string</code></p>
<p>Required. Name of the parent resource for the entitlement. Possible formats:</p>
<ul>
<li><code>organizations/{organization-number}/locations/{region}</code></li>
<li><code>folders/{folder-number}/locations/{region}</code></li>
<li><code>projects/{project-id|project-number}/locations/{region}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>entitlement_id</code></td>
<td><p><code>string</code></p>
<p>Required. The ID to use for this entitlement. This becomes the last part of the resource name.</p>
<p>This value should be 4-63 characters in length, and valid characters are "[a-z]", "[0-9]", and "-". The first character should be from [a-z].</p>
<p>This value should be unique among all other entitlements under the specified <code>parent</code> .</p></td>
</tr>
<tr class="odd">
<td><code>entitlement</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement"><code>Entitlement</code></a></p>
<p>Required. The resource being created</p></td>
</tr>
<tr class="even">
<td><code>request_id</code></td>
<td><p><code>string</code></p>
<p>Optional. An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server knows to ignore the request if it has already been completed. The server guarantees this for at least 60 minutes after the first request.</p>
<p>For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, ignores the second request and returns the previous operation's response. This prevents clients from accidentally creating duplicate entitlements.</p>
<p>The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).</p></td>
</tr>
</tbody>
</table>

## CreateGrantRequest

Message for creating a grant

| Fields       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|--------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`     | `string` Required. Name of the parent entitlement for which this grant is being requested.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| `grant`      | [`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant) Required. The resource being created.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `request_id` | `string` Optional. An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server knows to ignore the request if it has already been completed. The server guarantees this for at least 60 minutes after the first request. For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, ignores the second request. This prevents clients from accidentally creating duplicate grants. The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000). |

## DeleteEntitlementRequest

Message for deleting an entitlement.

| Fields       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|--------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`       | `string` Required. Name of the resource.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `request_id` | `string` Optional. An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server knows to ignore the request if it has already been completed. The server guarantees this for at least 60 minutes after the first request. For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, ignores the second request. The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000). |
| `force`      | `bool` Optional. If set to true, any child grant under this entitlement is also deleted. (Otherwise, the request only works if the entitlement has no child grant.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

## DenyGrantRequest

Request message for `DenyGrant` method.

| Fields   |                                                                                                                                                                                |
|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`   | `string` Required. Name of the grant resource which is being denied.                                                                                                           |
| `reason` | `string` Optional. The reason for denying this grant. This is required if `require_approver_justification` field of the `ManualApprovals` workflow used in this grant is true. |

## Entitlement

An entitlement defines the eligibility of a set of users to obtain predefined access for some time possibly after going through an approval workflow.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>Identifier. Name of the entitlement. Possible formats:</p>
<ul>
<li><code>organizations/{organization-number}/locations/{region}/entitlements/{entitlement-id}</code></li>
<li><code>folders/{folder-number}/locations/{region}/entitlements/{entitlement-id}</code></li>
<li><code>projects/{project-id|project-number}/locations/{region}/entitlements/{entitlement-id}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>create_time</code></td>
<td><p><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a></p>
<p>Output only. Create time stamp.</p></td>
</tr>
<tr class="odd">
<td><code>update_time</code></td>
<td><p><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a></p>
<p>Output only. Update time stamp.</p></td>
</tr>
<tr class="even">
<td><code>eligible_users[]</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.AccessControlEntry"><code>AccessControlEntry</code></a></p>
<p>Optional. Who can create grants using this entitlement. This list should contain at most one entry.</p></td>
</tr>
<tr class="odd">
<td><code>approval_workflow</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ApprovalWorkflow"><code>ApprovalWorkflow</code></a></p>
<p>Optional. The approvals needed before access are granted to a requester. No approvals are needed if this field is null.</p></td>
</tr>
<tr class="even">
<td><code>privileged_access</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.PrivilegedAccess"><code>PrivilegedAccess</code></a></p>
<p>Required. The access granted to a requester on successful approval.</p></td>
</tr>
<tr class="odd">
<td><code>max_request_duration</code></td>
<td><p><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#duration"><code>Duration</code></a></p>
<p>Required. The maximum amount of time that access is granted for a request. A requester can ask for a shorter duration but never a longer one. The supported range is between 30 minutes and 168 hours (7 days).</p></td>
</tr>
<tr class="even">
<td><code>state</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement.State"><code>State</code></a></p>
<p>Output only. Current state of this entitlement.</p></td>
</tr>
<tr class="odd">
<td><code>requester_justification_config</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement.RequesterJustificationConfig"><code>RequesterJustificationConfig</code></a></p>
<p>Required. The manner in which the requester should provide a justification for requesting access.</p></td>
</tr>
<tr class="even">
<td><code>additional_notification_targets</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement.AdditionalNotificationTargets"><code>AdditionalNotificationTargets</code></a></p>
<p>Optional. Additional email addresses to be notified based on actions taken.</p></td>
</tr>
<tr class="odd">
<td><code>etag</code></td>
<td><p><code>string</code></p>
<p>An <code>etag</code> is used for optimistic concurrency control as a way to prevent simultaneous updates to the same entitlement. An <code>etag</code> is returned in the response to <code>GetEntitlement</code> and the caller should put the <code>etag</code> in the request to <code>UpdateEntitlement</code> so that their change is applied on the same version. If this field is omitted or if there is a mismatch while updating an entitlement, then the server rejects the request.</p></td>
</tr>
</tbody>
</table>

## AdditionalNotificationTargets

`AdditionalNotificationTargets` includes email addresses to be notified.

| Fields                         |                                                                                                              |
|--------------------------------|--------------------------------------------------------------------------------------------------------------|
| `admin_email_recipients[]`     | `string` Optional. Additional email addresses to be notified when a principal (requester) is granted access. |
| `requester_email_recipients[]` | `string` Optional. Additional email address to be notified about an eligible entitlement.                    |

## RequesterJustificationConfig

Defines how a requester must provide a justification when requesting access.

| Fields                                                                                                                                                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                   |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `justification_type` . This is a required field and the user must explicitly opt out if a justification from the requester isn't mandatory. `justification_type` can be only one of the following: |                                                                                                                                                                                                                                                                                                                                                                                                   |
| `not_mandatory`                                                                                                                                                                                                | [`NotMandatory`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement.RequesterJustificationConfig.NotMandatory) This option means the requester isn't required to provide a justification.                                                                                                       |
| `unstructured`                                                                                                                                                                                                 | [`Unstructured`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement.RequesterJustificationConfig.Unstructured) This option means the requester must provide a string as justification. If this is selected, the server allows the requester to provide a justification but doesn't validate it. |

## NotMandatory

This type has no fields.

The justification is not mandatory but can be provided in any of the supported formats.

## Unstructured

This type has no fields.

The requester has to provide a justification in the form of a string.

## State

Different states an entitlement can be in.

| Enums               |                                                                |
|---------------------|----------------------------------------------------------------|
| `STATE_UNSPECIFIED` | Unspecified state. This value is never returned by the server. |
| `CREATING`          | The entitlement is being created.                              |
| `AVAILABLE`         | The entitlement is available for requesting access.            |
| `DELETING`          | The entitlement is being deleted.                              |
| `DELETED`           | The entitlement has been deleted.                              |
| `UPDATING`          | The entitlement is being updated.                              |

## GetEntitlementRequest

Message for getting an entitlement.

| Fields |                                          |
|--------|------------------------------------------|
| `name` | `string` Required. Name of the resource. |

## GetGrantRequest

Message for getting a grant.

| Fields |                                          |
|--------|------------------------------------------|
| `name` | `string` Required. Name of the resource. |

## Grant

A grant represents a request from a user for obtaining the access specified in an entitlement they are eligible for.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>Identifier. Name of this grant. Possible formats:</p>
<ul>
<li><code>organizations/{organization-number}/locations/{region}/entitlements/{entitlement-id}/grants/{grant-id}</code></li>
<li><code>folders/{folder-number}/locations/{region}/entitlements/{entitlement-id}/grants/{grant-id}</code></li>
<li><code>projects/{project-id|project-number}/locations/{region}/entitlements/{entitlement-id}/grants/{grant-id}</code></li>
</ul>
<p>The last segment of this name ( <code>{grant-id}</code> ) is autogenerated.</p></td>
</tr>
<tr class="even">
<td><code>create_time</code></td>
<td><p><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a></p>
<p>Output only. Create time stamp.</p></td>
</tr>
<tr class="odd">
<td><code>update_time</code></td>
<td><p><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a></p>
<p>Output only. Update time stamp.</p></td>
</tr>
<tr class="even">
<td><code>requester</code></td>
<td><p><code>string</code></p>
<p>Output only. Username of the user who created this grant.</p></td>
</tr>
<tr class="odd">
<td><code>requested_duration</code></td>
<td><p><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#duration"><code>Duration</code></a></p>
<p>Required. The amount of time access is needed for. This value should be shorter than the <code>max_request_duration</code> value of the entitlement.</p></td>
</tr>
<tr class="even">
<td><code>justification</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Justification"><code>Justification</code></a></p>
<p>Optional. Justification of why this access is needed.</p></td>
</tr>
<tr class="odd">
<td><code>state</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.State"><code>State</code></a></p>
<p>Output only. Current state of this grant.</p></td>
</tr>
<tr class="even">
<td><code>timeline</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline"><code>Timeline</code></a></p>
<p>Output only. Timeline of this grant.</p></td>
</tr>
<tr class="odd">
<td><code>privileged_access</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.PrivilegedAccess"><code>PrivilegedAccess</code></a></p>
<p>Output only. The access that would be granted by this grant.</p></td>
</tr>
<tr class="even">
<td><code>audit_trail</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.AuditTrail"><code>AuditTrail</code></a></p>
<p>Output only. Audit trail of access provided by this grant. If unspecified then access was never granted.</p></td>
</tr>
<tr class="odd">
<td><code>additional_email_recipients[]</code></td>
<td><p><code>string</code></p>
<p>Optional. Additional email addresses to notify for all the actions performed on the grant.</p></td>
</tr>
<tr class="even">
<td><code>externally_modified</code></td>
<td><p><code>bool</code></p>
<p>Output only. Flag set by the PAM system to indicate that policy bindings made by this grant have been modified from outside PAM.</p>
<p>After it is set, this flag remains set forever irrespective of the grant state. A <code>true</code> value here indicates that PAM no longer has any certainty on the access a user has because of this grant.</p></td>
</tr>
</tbody>
</table>

## AuditTrail

Audit trail for the access provided by this grant.

| Fields               |                                                                                                                                                                                                                                                                           |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `access_grant_time`  | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time at which access was given.                                                                                                                                        |
| `access_remove_time` | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time at which the system removed access. This could be because of an automatic expiry or because of a revocation. If unspecified, then access hasn't been removed yet. |

## State

Different states a grant can be in.

| Enums               |                                                                                                                                         |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| `STATE_UNSPECIFIED` | Unspecified state. This value is never returned by the server.                                                                          |
| `APPROVAL_AWAITED`  | The entitlement had an approval workflow configured and this grant is waiting for the workflow to complete.                             |
| `DENIED`            | The approval workflow completed with a denied result. No access is granted for this grant. This is a terminal state.                    |
| `SCHEDULED`         | The approval workflow completed successfully with an approved result or none was configured. Access is provided at an appropriate time. |
| `ACTIVATING`        | Access is being given.                                                                                                                  |
| `ACTIVE`            | Access was successfully given and is currently active.                                                                                  |
| `ACTIVATION_FAILED` | The system could not give access due to a non-retriable error. This is a terminal state.                                                |
| `EXPIRED`           | Expired after waiting for the approval workflow to complete. This is a terminal state.                                                  |
| `REVOKING`          | Access is being revoked.                                                                                                                |
| `REVOKED`           | Access was revoked by a user. This is a terminal state.                                                                                 |
| `ENDED`             | System took back access as the requested duration was over. This is a terminal state.                                                   |
| `WITHDRAWING`       | Access is being withdrawn.                                                                                                              |
| `WITHDRAWN`         | Grant was withdrawn by the grant owner. This is a terminal state.                                                                       |

## Timeline

Timeline of a grant describing what happened to it and when.

| Fields     |                                                                                                                                                                                                                                                                                                                                                                                                          |
|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `events[]` | [`Event`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event) Output only. The events that have occurred on this grant. This list contains entries in the same order as they occurred. The first entry is always be of type `Requested` and there is always at least one entry in this array. |

## Event

A single operation on the grant.

| Fields                                                          |                                                                                                                                                                                                                                                                                   |
|-----------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `event_time`                                                    | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time (as recorded at server) when this event occurred.                                                                                                                         |
| Union field `event` . `event` can be only one of the following: |                                                                                                                                                                                                                                                                                   |
| `requested`                                                     | [`Requested`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Requested) The grant was requested.                                                                   |
| `approved`                                                      | [`Approved`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Approved) The grant was approved.                                                                      |
| `denied`                                                        | [`Denied`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Denied) The grant was denied.                                                                            |
| `revoked`                                                       | [`Revoked`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Revoked) The grant was revoked.                                                                         |
| `scheduled`                                                     | [`Scheduled`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Scheduled) The grant has been scheduled to give access.                                               |
| `activated`                                                     | [`Activated`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Activated) The grant was successfully activated to give access.                                       |
| `activation_failed`                                             | [`ActivationFailed`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.ActivationFailed) There was a non-retriable error while trying to give access.                 |
| `expired`                                                       | [`Expired`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Expired) The approval workflow did not complete in the necessary duration, and so the grant is expired. |
| `ended`                                                         | [`Ended`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Ended) Access given by the grant ended automatically as the approved duration was over.                   |
| `externally_modified`                                           | [`ExternallyModified`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.ExternallyModified) The policy bindings made by grant have been modified outside of PAM.     |
| `withdrawn`                                                     | [`Withdrawn`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant.Timeline.Event.Withdrawn) The grant was withdrawn.                                                                   |

## Activated

This type has no fields.

An event representing that the grant was successfully activated.

## ActivationFailed

An event representing that the grant activation failed.

| Fields  |                                                                                                                                                                    |
|---------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `error` | [`Status`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.rpc#google.rpc.Status) Output only. The error that occurred while activating the grant. |

## Approved

An event representing that the grant was approved.

| Fields   |                                                                                    |
|----------|------------------------------------------------------------------------------------|
| `reason` | `string` Output only. The reason provided by the approver for approving the grant. |
| `actor`  | `string` Output only. Username of the user who approved the grant.                 |

## Denied

An event representing that the grant was denied.

| Fields   |                                                                                  |
|----------|----------------------------------------------------------------------------------|
| `reason` | `string` Output only. The reason provided by the approver for denying the grant. |
| `actor`  | `string` Output only. Username of the user who denied the grant.                 |

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

| Fields        |                                                                                                                                                                                                                         |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `expire_time` | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time at which this grant expires unless the approval workflow completes. If omitted, then the request never expires. |

## Revoked

An event representing that the grant was revoked.

| Fields   |                                                                               |
|----------|-------------------------------------------------------------------------------|
| `reason` | `string` Output only. The reason provided by the user for revoking the grant. |
| `actor`  | `string` Output only. Username of the user who revoked the grant.             |

## Scheduled

An event representing that the grant has been scheduled to be activated later.

| Fields                      |                                                                                                                                         |
|-----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| `scheduled_activation_time` | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time at which the access is granted. |

## Withdrawn

This type has no fields.

An event representing that the grant was withdrawn.

## Justification

Justification represents a justification for requesting access.

| Fields                                                                          |                                                                                                                                                     |
|---------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `justification` . `justification` can be only one of the following: |                                                                                                                                                     |
| `unstructured_justification`                                                    | `string` A free form textual justification. The system only ensures that this is not empty. No other kind of validation is performed on the string. |

## ListEntitlementsRequest

Message for requesting list of entitlements.

| Fields       |                                                                                                                                               |
|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`     | `string` Required. The parent which owns the entitlement resources.                                                                           |
| `page_size`  | `int32` Optional. Requested page size. Server may return fewer items than requested. If unspecified, the server picks an appropriate default. |
| `page_token` | `string` Optional. A token identifying a page of results the server should return.                                                            |
| `filter`     | `string` Optional. Filtering results.                                                                                                         |
| `order_by`   | `string` Optional. Hint for how to order the results.                                                                                         |

## ListEntitlementsResponse

Message for response to listing entitlements.

| Fields            |                                                                                                                                                                                                 |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `entitlements[]`  | [`Entitlement`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement) The list of entitlements. |
| `next_page_token` | `string` A token identifying a page of results the server should return.                                                                                                                        |
| `unreachable[]`   | `string` Locations that could not be reached.                                                                                                                                                   |

## ListGrantsRequest

Message for requesting list of grants.

| Fields       |                                                                                                                                                   |
|--------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`     | `string` Required. The parent resource which owns the grants.                                                                                     |
| `page_size`  | `int32` Optional. Requested page size. The server may return fewer items than requested. If unspecified, the server picks an appropriate default. |
| `page_token` | `string` Optional. A token identifying a page of results the server should return.                                                                |
| `filter`     | `string` Optional. Filtering results.                                                                                                             |
| `order_by`   | `string` Optional. Hint for how to order the results                                                                                              |

## ListGrantsResponse

Message for response to listing grants.

| Fields            |                                                                                                                                                                               |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `grants[]`        | [`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant) The list of grants. |
| `next_page_token` | `string` A token identifying a page of results the server should return.                                                                                                      |
| `unreachable[]`   | `string` Locations that could not be reached.                                                                                                                                 |

## ManualApprovals

A manual approval workflow where users who are designated as approvers need to call the `ApproveGrant` / `DenyGrant` APIs for a grant. The workflow can consist of multiple serial steps where each step defines who can act as approver in that step and how many of those users should approve before the workflow moves to the next step.

This can be used to create approval workflows such as:

- Require an approval from any user in a group G.
- Require an approval from any k number of users from a Group G.
- Require an approval from any user in a group G and then from a user U.

A single user might be part of the `approvers` ACL for multiple steps in this workflow, but they can only approve once and that approval is only considered to satisfy the approval step at which it was granted.

| Fields                           |                                                                                                                                                                                                                                                                                                                    |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `require_approver_justification` | `bool` Optional. Do the approvers need to provide a justification for their actions?                                                                                                                                                                                                                               |
| `steps[]`                        | [`Step`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.ManualApprovals.Step) Optional. List of approval steps in this workflow. These steps are followed in the specified order sequentially. Only 1 step is supported. |

## Step

Step represents a logical step in a manual approval workflow.

| Fields                        |                                                                                                                                                                                                                                                                                      |
|-------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `approvers[]`                 | [`AccessControlEntry`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.AccessControlEntry) Optional. The potential set of approvers in this step. This list must contain at most one entry. |
| `approvals_needed`            | `int32` Required. How many users from the above list need to approve. If there aren't enough distinct users in the list, then the workflow indefinitely blocks. Should always be greater than 0. 1 is the only supported value.                                                      |
| `approver_email_recipients[]` | `string` Optional. Additional email addresses to be notified when a grant is pending approval.                                                                                                                                                                                       |

## OperationMetadata

Represents the metadata of the long-running operation.

| Fields                   |                                                                                                                                                                                                                                                                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `create_time`            | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time the operation was created.                                                                                                                                                                                                                                                      |
| `end_time`               | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time the operation finished running.                                                                                                                                                                                                                                                 |
| `target`                 | `string` Output only. Server-defined resource path for the target of the operation.                                                                                                                                                                                                                                                                                                     |
| `verb`                   | `string` Output only. Name of the verb executed by the operation.                                                                                                                                                                                                                                                                                                                       |
| `status_message`         | `string` Output only. Human-readable status of the operation, if any.                                                                                                                                                                                                                                                                                                                   |
| `requested_cancellation` | `bool` Output only. Identifies whether the user has requested cancellation of the operation. Operations that have been cancelled successfully have \[Operation.error\]\[\] value with a [`google.rpc.Status.code`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.rpc#google.rpc.Status.FIELDS.int32.google.rpc.Status.code) of 1, corresponding to `Code.CANCELLED` . |
| `api_version`            | `string` Output only. API version used to start the operation.                                                                                                                                                                                                                                                                                                                          |

## PrivilegedAccess

Privileged access that this service can be used to gate.

| Fields                                                                      |                                                                                                                                                                                                                                         |
|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `access_type` . `access_type` can be only one of the following: |                                                                                                                                                                                                                                         |
| `gcp_iam_access`                                                            | [`GcpIamAccess`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.PrivilegedAccess.GcpIamAccess) Access to a Google Cloud resource through IAM. |

## GcpIamAccess

`GcpIamAccess` represents IAM based access control on a Google Cloud resource. Refer to <https://cloud.google.com/iam/docs> to understand more about IAM.

| Fields            |                                                                                                                                                                                                                                                                   |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resource_type`   | `string` Required. The type of this resource.                                                                                                                                                                                                                     |
| `resource`        | `string` Required. Name of the resource.                                                                                                                                                                                                                          |
| `role_bindings[]` | [`RoleBinding`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.PrivilegedAccess.GcpIamAccess.RoleBinding) Required. Role bindings that are created on successful grant. |

## RoleBinding

IAM role bindings that are created after a successful grant.

| Fields                 |                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `role`                 | `string` Required. IAM role to be granted. <https://cloud.google.com/iam/docs/roles-overview> .                                                                                                                                                                                                                                                                                                                                    |
| `condition_expression` | `string` Optional. The expression field of the IAM condition to be associated with the role. If specified, a user with an active grant for this entitlement is able to access the resource only if this condition evaluates to true for their request. This field uses the same CEL format as IAM and supports all attributes that IAM supports, except tags. <https://cloud.google.com/iam/docs/conditions-overview#attributes> . |

## RevokeGrantRequest

Request message for `RevokeGrant` method.

| Fields   |                                                                       |
|----------|-----------------------------------------------------------------------|
| `name`   | `string` Required. Name of the grant resource which is being revoked. |
| `reason` | `string` Optional. The reason for revoking this grant.                |

## SearchEntitlementsRequest

Request message for `SearchEntitlements` method.

| Fields               |                                                                                                                                                                                                                                                                                            |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`             | `string` Required. The parent which owns the entitlement resources.                                                                                                                                                                                                                        |
| `caller_access_type` | [`CallerAccessType`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.SearchEntitlementsRequest.CallerAccessType) Required. Only entitlements where the calling user has this access are returned. |
| `filter`             | `string` Optional. Only entitlements matching this filter are returned in the response.                                                                                                                                                                                                    |
| `page_size`          | `int32` Optional. Requested page size. The server may return fewer items than requested. If unspecified, the server picks an appropriate default.                                                                                                                                          |
| `page_token`         | `string` Optional. A token identifying a page of results the server should return.                                                                                                                                                                                                         |

## CallerAccessType

Different types of access a user can have on the entitlement resource.

| Enums                            |                                                                            |
|----------------------------------|----------------------------------------------------------------------------|
| `CALLER_ACCESS_TYPE_UNSPECIFIED` | Unspecified access type.                                                   |
| `GRANT_REQUESTER`                | The user has access to create grants using this entitlement.               |
| `GRANT_APPROVER`                 | The user has access to approve/deny grants created under this entitlement. |

## SearchEntitlementsResponse

Response message for `SearchEntitlements` method.

| Fields            |                                                                                                                                                                                                 |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `entitlements[]`  | [`Entitlement`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement) The list of entitlements. |
| `next_page_token` | `string` A token identifying a page of results the server should return.                                                                                                                        |

## SearchGrantsRequest

Request message for `SearchGrants` method.

| Fields                |                                                                                                                                                                                                                                                                                                                         |
|-----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`              | `string` Required. The parent which owns the grant resources.                                                                                                                                                                                                                                                           |
| `caller_relationship` | [`CallerRelationshipType`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.SearchGrantsRequest.CallerRelationshipType) Required. Only grants which the caller is related to by this relationship are returned in the response. |
| `filter`              | `string` Optional. Only grants matching this filter are returned in the response.                                                                                                                                                                                                                                       |
| `page_size`           | `int32` Optional. Requested page size. The server may return fewer items than requested. If unspecified, server picks an appropriate default.                                                                                                                                                                           |
| `page_token`          | `string` Optional. A token identifying a page of results the server should return.                                                                                                                                                                                                                                      |

## CallerRelationshipType

Different types of relationships a user can have with a grant.

| Enums                                  |                                                                                                                  |
|----------------------------------------|------------------------------------------------------------------------------------------------------------------|
| `CALLER_RELATIONSHIP_TYPE_UNSPECIFIED` | Unspecified caller relationship type.                                                                            |
| `HAD_CREATED`                          | The user created this grant by calling `CreateGrant` earlier.                                                    |
| `CAN_APPROVE`                          | The user is an approver for the entitlement that this grant is parented under and can currently approve/deny it. |
| `HAD_APPROVED`                         | The caller had successfully approved/denied this grant earlier.                                                  |

## SearchGrantsResponse

Response message for `SearchGrants` method.

| Fields            |                                                                                                                                                                               |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `grants[]`        | [`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Grant) The list of grants. |
| `next_page_token` | `string` A token identifying a page of results the server should return.                                                                                                      |

## UpdateEntitlementRequest

Message for updating an entitlement.

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `entitlement` | [`Entitlement`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1#google.cloud.privilegedaccessmanager.v1.Entitlement) Required. The entitlement resource that is updated.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| `update_mask` | [`FieldMask`](https://protobuf.dev/reference/protobuf/google.protobuf/#field-mask) Required. The list of fields to update. A field is overwritten if, and only if, it is in the mask. Any immutable fields set in the mask are ignored by the server. Repeated fields and map fields are only allowed in the last position of a `paths` string and overwrite the existing values. Hence an update to a repeated field or a map should contain the entire list of values. The fields specified in the update_mask are relative to the resource and not to the request. (e.g. `MaxRequestDuration` ; *not* `entitlement.MaxRequestDuration` ) A value of '\*' for this field refers to full replacement of the resource. |
