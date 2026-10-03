---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta
title: Package google.cloud.privilegedaccessmanager.v1beta
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

- [`PrivilegedAccessManager`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager) (interface)
- [`AccessControlEntry`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.AccessControlEntry) (message)
- [`ApprovalWorkflow`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ApprovalWorkflow) (message)
- [`ApproveGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ApproveGrantRequest) (message)
- [`CheckOnboardingStatusRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.CheckOnboardingStatusRequest) (message)
- [`CheckOnboardingStatusResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.CheckOnboardingStatusResponse) (message)
- [`CheckOnboardingStatusResponse.Finding`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.CheckOnboardingStatusResponse.Finding) (message)
- [`CheckOnboardingStatusResponse.Finding.IAMAccessDenied`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.CheckOnboardingStatusResponse.Finding.IAMAccessDenied) (message)
- [`CreateEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.CreateEntitlementRequest) (message)
- [`CreateGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.CreateGrantRequest) (message)
- [`DeleteEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.DeleteEntitlementRequest) (message)
- [`DenyGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.DenyGrantRequest) (message)
- [`Entitlement`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement) (message)
- [`Entitlement.AdditionalNotificationTargets`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement.AdditionalNotificationTargets) (message)
- [`Entitlement.RequesterJustificationConfig`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement.RequesterJustificationConfig) (message)
- [`Entitlement.RequesterJustificationConfig.NotMandatory`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement.RequesterJustificationConfig.NotMandatory) (message)
- [`Entitlement.RequesterJustificationConfig.Unstructured`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement.RequesterJustificationConfig.Unstructured) (message)
- [`Entitlement.State`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement.State) (enum)
- [`FetchEffectiveSettingsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsRequest) (message)
- [`FetchEffectiveSettingsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse) (message)
- [`FetchEffectiveSettingsResponse.EmailNotificationSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.EmailNotificationSettings) (message)
- [`FetchEffectiveSettingsResponse.EmailNotificationSettings.CustomNotificationBehavior`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.EmailNotificationSettings.CustomNotificationBehavior) (message)
- [`FetchEffectiveSettingsResponse.EmailNotificationSettings.CustomNotificationBehavior.AdminNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.EmailNotificationSettings.CustomNotificationBehavior.AdminNotifications) (message)
- [`FetchEffectiveSettingsResponse.EmailNotificationSettings.CustomNotificationBehavior.ApproverNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.EmailNotificationSettings.CustomNotificationBehavior.ApproverNotifications) (message)
- [`FetchEffectiveSettingsResponse.EmailNotificationSettings.CustomNotificationBehavior.RequesterNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.EmailNotificationSettings.CustomNotificationBehavior.RequesterNotifications) (message)
- [`FetchEffectiveSettingsResponse.EmailNotificationSettings.DisableAllNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.EmailNotificationSettings.DisableAllNotifications) (message)
- [`FetchEffectiveSettingsResponse.ServiceAccountApproverSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.ServiceAccountApproverSettings) (message)
- [`GetEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.GetEntitlementRequest) (message)
- [`GetGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.GetGrantRequest) (message)
- [`GetSettingsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.GetSettingsRequest) (message)
- [`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant) (message)
- [`Grant.ActivationTrigger`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.ActivationTrigger) (message)
- [`Grant.AuditTrail`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.AuditTrail) (message)
- [`Grant.State`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.State) (enum)
- [`Grant.Timeline`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline) (message)
- [`Grant.Timeline.Event`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event) (message)
- [`Grant.Timeline.Event.Activated`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Activated) (message)
- [`Grant.Timeline.Event.ActivationFailed`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.ActivationFailed) (message)
- [`Grant.Timeline.Event.Approved`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Approved) (message)
- [`Grant.Timeline.Event.Denied`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Denied) (message)
- [`Grant.Timeline.Event.Ended`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Ended) (message)
- [`Grant.Timeline.Event.Expired`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Expired) (message)
- [`Grant.Timeline.Event.ExternallyModified`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.ExternallyModified) (message)
- [`Grant.Timeline.Event.Requested`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Requested) (message)
- [`Grant.Timeline.Event.Revoked`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Revoked) (message)
- [`Grant.Timeline.Event.Scheduled`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Scheduled) (message)
- [`Grant.Timeline.Event.Withdrawn`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Withdrawn) (message)
- [`Justification`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Justification) (message)
- [`ListEntitlementsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ListEntitlementsRequest) (message)
- [`ListEntitlementsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ListEntitlementsResponse) (message)
- [`ListGrantsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ListGrantsRequest) (message)
- [`ListGrantsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ListGrantsResponse) (message)
- [`ManualApprovals`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ManualApprovals) (message)
- [`ManualApprovals.Step`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ManualApprovals.Step) (message)
- [`OperationMetadata`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.OperationMetadata) (message)
- [`PrivilegedAccess`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccess) (message)
- [`PrivilegedAccess.GcpIamAccess`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccess.GcpIamAccess) (message)
- [`PrivilegedAccess.GcpIamAccess.RoleBinding`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccess.GcpIamAccess.RoleBinding) (message)
- [`RequestedPrivilegedAccess`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.RequestedPrivilegedAccess) (message)
- [`RequestedPrivilegedAccess.GcpIamAccess`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.RequestedPrivilegedAccess.GcpIamAccess) (message)
- [`RequestedPrivilegedAccess.GcpIamAccess.AccessRestrictions`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.RequestedPrivilegedAccess.GcpIamAccess.AccessRestrictions) (message)
- [`RequestedPrivilegedAccess.GcpIamAccess.RoleBinding`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.RequestedPrivilegedAccess.GcpIamAccess.RoleBinding) (message)
- [`RevokeGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.RevokeGrantRequest) (message)
- [`SearchEntitlementsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.SearchEntitlementsRequest) (message)
- [`SearchEntitlementsRequest.CallerAccessType`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.SearchEntitlementsRequest.CallerAccessType) (enum)
- [`SearchEntitlementsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.SearchEntitlementsResponse) (message)
- [`SearchGrantsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.SearchGrantsRequest) (message)
- [`SearchGrantsRequest.CallerRelationshipType`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.SearchGrantsRequest.CallerRelationshipType) (enum)
- [`SearchGrantsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.SearchGrantsResponse) (message)
- [`Settings`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings) (message)
- [`Settings.EmailNotificationSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings) (message)
- [`Settings.EmailNotificationSettings.CustomNotificationBehavior`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior) (message)
- [`Settings.EmailNotificationSettings.CustomNotificationBehavior.AdminNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.AdminNotifications) (message)
- [`Settings.EmailNotificationSettings.CustomNotificationBehavior.ApproverNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.ApproverNotifications) (message)
- [`Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) (enum)
- [`Settings.EmailNotificationSettings.CustomNotificationBehavior.RequesterNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.RequesterNotifications) (message)
- [`Settings.EmailNotificationSettings.DisableAllNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.DisableAllNotifications) (message)
- [`Settings.ServiceAccountApproverSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.ServiceAccountApproverSettings) (message)
- [`UpdateEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.UpdateEntitlementRequest) (message)
- [`UpdateSettingsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.UpdateSettingsRequest) (message)
- [`WithdrawGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.WithdrawGrantRequest) (message)

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

`rpc ApproveGrant( `[`ApproveGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ApproveGrantRequest)` ) returns ( `[`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant)` )`

`ApproveGrant` is used to approve a grant. This method can only be called on a grant when it's in the `APPROVAL_AWAITED` state. This operation can't be undone.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**CheckOnboardingStatus**

`rpc CheckOnboardingStatus( `[`CheckOnboardingStatusRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.CheckOnboardingStatusRequest)` ) returns ( `[`CheckOnboardingStatusResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.CheckOnboardingStatusResponse)` )`

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

`rpc CreateEntitlement( `[`CreateEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.CreateEntitlementRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.longrunning#google.longrunning.Operation)` )`

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

`rpc CreateGrant( `[`CreateGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.CreateGrantRequest)` ) returns ( `[`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant)` )`

Creates a grant in a given project, folder, or organization and location.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**DeleteEntitlement**

`rpc DeleteEntitlement( `[`DeleteEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.DeleteEntitlementRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.longrunning#google.longrunning.Operation)` )`

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

`rpc DenyGrant( `[`DenyGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.DenyGrantRequest)` ) returns ( `[`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant)` )`

`DenyGrant` is used to deny a grant. This method can only be called on a grant when it's in the `APPROVAL_AWAITED` state. This operation can't be undone.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**FetchEffectiveSettings**

`rpc FetchEffectiveSettings( `[`FetchEffectiveSettingsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsRequest)` ) returns ( `[`FetchEffectiveSettingsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse)` )`

`FetchEffectiveSettings` returns the effective PAM Settings for the given project, folder, or organization.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `privilegedaccessmanager.settings.fetchEffective`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**GetEntitlement**

`rpc GetEntitlement( `[`GetEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.GetEntitlementRequest)` ) returns ( `[`Entitlement`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement)` )`

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

`rpc GetGrant( `[`GetGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.GetGrantRequest)` ) returns ( `[`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant)` )`

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

**GetSettings**

`rpc GetSettings( `[`GetSettingsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.GetSettingsRequest)` ) returns ( `[`Settings`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings)` )`

`GetSettings` returns the PAM Settings for the given project, folder, or organization.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `privilegedaccessmanager.settings.get`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**ListEntitlements**

`rpc ListEntitlements( `[`ListEntitlementsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ListEntitlementsRequest)` ) returns ( `[`ListEntitlementsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ListEntitlementsResponse)` )`

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

`rpc ListGrants( `[`ListGrantsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ListGrantsRequest)` ) returns ( `[`ListGrantsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ListGrantsResponse)` )`

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

`rpc RevokeGrant( `[`RevokeGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.RevokeGrantRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.longrunning#google.longrunning.Operation)` )`

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

`rpc SearchEntitlements( `[`SearchEntitlementsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.SearchEntitlementsRequest)` ) returns ( `[`SearchEntitlementsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.SearchEntitlementsResponse)` )`

`SearchEntitlements` returns entitlements on which the caller has the specified access.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**SearchGrants**

`rpc SearchGrants( `[`SearchGrantsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.SearchGrantsRequest)` ) returns ( `[`SearchGrantsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.SearchGrantsResponse)` )`

`SearchGrants` returns grants that are related to the calling user in the specified way.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**UpdateEntitlement**

`rpc UpdateEntitlement( `[`UpdateEntitlementRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.UpdateEntitlementRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.longrunning#google.longrunning.Operation)` )`

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

**UpdateSettings**

`rpc UpdateSettings( `[`UpdateSettingsRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.UpdateSettingsRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.longrunning#google.longrunning.Operation)` )`

`UpdateSettings` updates the PAM Settings resource specified in the request. Updated fields in the settings need to be specified in an update mask. The following fields are not supported for updates: \* Settings name \* Create time \* Update time \* Etag

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `privilegedaccessmanager.settings.update`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**WithdrawGrant**

`rpc WithdrawGrant( `[`WithdrawGrantRequest`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.WithdrawGrantRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.longrunning#google.longrunning.Operation)` )`

`WithdrawGrant` is used to immediately withdraw the grant. This method can be called when the grant is in a non-terminal state.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

## AccessControlEntry

`AccessControlEntry` is used to control who can do some operation.

| Fields         |                                                                                                                                                                                                                           |
|----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `principals[]` | `string` Optional. Users who are allowed for the operation. Each entry should be a valid v1 IAM principal identifier. The format for these is documented at: <https://cloud.google.com/iam/docs/principal-identifiers#v1> |

## ApprovalWorkflow

Different types of approval workflows that can be used to gate privileged access granting.

| Fields                                                                                  |                                                                                                                                                                                                                                                                              |
|-----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `approval_workflow` . `approval_workflow` can be only one of the following: |                                                                                                                                                                                                                                                                              |
| `manual_approvals`                                                                      | [`ManualApprovals`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ManualApprovals) An approval workflow where users designated as approvers review and act on the grants. |

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

| Fields            |                                                                                                                                                                                                                                                                                                                                                                           |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `service_account` | `string` The service account that PAM uses to act on this resource.                                                                                                                                                                                                                                                                                                       |
| `findings[]`      | [`Finding`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.CheckOnboardingStatusResponse.Finding) List of issues that are preventing PAM from functioning for this resource and need to be fixed to complete onboarding. Some issues might not be detected or reported. |

## Finding

Finding represents an issue which prevents PAM from functioning properly for this resource.

| Fields                                                                        |                                                                                                                                                                                                                                                                                        |
|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `finding_type` . `finding_type` can be only one of the following: |                                                                                                                                                                                                                                                                                        |
| `iam_access_denied`                                                           | [`IAMAccessDenied`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.CheckOnboardingStatusResponse.Finding.IAMAccessDenied) PAM's service account is being denied access by Cloud IAM. |

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
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement"><code>Entitlement</code></a></p>
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
| `grant`      | [`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant) Required. The resource being created.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
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
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.AccessControlEntry"><code>AccessControlEntry</code></a></p>
<p>Optional. Who can create grants using this entitlement. This list should contain at most one entry.</p></td>
</tr>
<tr class="odd">
<td><code>approval_workflow</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ApprovalWorkflow"><code>ApprovalWorkflow</code></a></p>
<p>Optional. The approvals needed before access are granted to a requester. No approvals are needed if this field is null.</p></td>
</tr>
<tr class="even">
<td><code>privileged_access</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccess"><code>PrivilegedAccess</code></a></p>
<p>Required. The access granted to a requester on successful approval.</p></td>
</tr>
<tr class="odd">
<td><code>max_request_duration</code></td>
<td><p><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#duration"><code>Duration</code></a></p>
<p>Required. The maximum amount of time that access is granted for a request. A requester can ask for a shorter duration but never a longer one. The supported range is between 30 minutes and 168 hours (7 days).</p></td>
</tr>
<tr class="even">
<td><code>state</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement.State"><code>State</code></a></p>
<p>Output only. Current state of this entitlement.</p></td>
</tr>
<tr class="odd">
<td><code>requester_justification_config</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement.RequesterJustificationConfig"><code>RequesterJustificationConfig</code></a></p>
<p>Required. The manner in which the requester should provide a justification for requesting access.</p></td>
</tr>
<tr class="even">
<td><code>additional_notification_targets</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement.AdditionalNotificationTargets"><code>AdditionalNotificationTargets</code></a></p>
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

| Fields                                                                                                                                                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                           |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `justification_type` . This is a required field and the user must explicitly opt out if a justification from the requester isn't mandatory. `justification_type` can be only one of the following: |                                                                                                                                                                                                                                                                                                                                                                                                           |
| `not_mandatory`                                                                                                                                                                                                | [`NotMandatory`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement.RequesterJustificationConfig.NotMandatory) This option means the requester isn't required to provide a justification.                                                                                                       |
| `unstructured`                                                                                                                                                                                                 | [`Unstructured`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement.RequesterJustificationConfig.Unstructured) This option means the requester must provide a string as justification. If this is selected, the server allows the requester to provide a justification but doesn't validate it. |

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

## FetchEffectiveSettingsRequest

Request message for `FetchEffectiveSettings` method.

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
<p>Required. The resource for which the effective settings is fetched, in one of the following formats:</p>
<ul>
<li><code>projects/{project-number|project-id}/locations/{region}</code></li>
<li><code>folders/{folder-number}/locations/{region}</code></li>
<li><code>organizations/{organization-number}/locations/{region}</code></li>
</ul></td>
</tr>
</tbody>
</table>

## FetchEffectiveSettingsResponse

The effective value of the settings at the given location resource, evaluated based on the crm resource hierarchy.

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
<p>Output only. The resource on which the settings are effective. Possible formats:</p>
<ul>
<li><code>projects/{project-number|project-id}/locations/{region}</code></li>
<li><code>folders/{folder-number}/locations/{region}</code></li>
<li><code>organizations/{organization-number}/locations/{region}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>service_account_approver_settings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.ServiceAccountApproverSettings"><code>ServiceAccountApproverSettings</code></a></p>
<p>Output only. Effective settings for allowing service account as approvers.</p></td>
</tr>
<tr class="odd">
<td><code>email_notification_settings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.EmailNotificationSettings"><code>EmailNotificationSettings</code></a></p>
<p>Output only. <code>EmailNotificationSettings</code> defines effective node-wide email notification preferences for various PAM events.</p></td>
</tr>
</tbody>
</table>

## EmailNotificationSettings

`EmailNotificationSettings` reflects the effective node-wide email notification settings.

| Fields                                                                                                                 |                                                                                                                                                                                                                                                                                                                       |
|------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `source`                                                                                                               | `string` Output only. The name of the resource from which the notification behavior is inherited. This field remains empty if the setting is not defined at either the parent or resource level, in which case PAM's default behavior is applied.                                                                     |
| Union field `notification_behavior` . Notification behavior. `notification_behavior` can be only one of the following: |                                                                                                                                                                                                                                                                                                                       |
| `disable_all_notifications`                                                                                            | [`DisableAllNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.EmailNotificationSettings.DisableAllNotifications) Output only. Disable all notifications.                |
| `custom_notification_behavior`                                                                                         | [`CustomNotificationBehavior`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.EmailNotificationSettings.CustomNotificationBehavior) Output only. Granular settings of notifications. |

## CustomNotificationBehavior

`CustomNotificationBehavior` reflects the granular notification delivery settings for specific events and personas, as configured by the admin.

| Fields                    |                                                                                                                                                                                                                                                                                                                                     |
|---------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `requester_notifications` | [`RequesterNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.EmailNotificationSettings.CustomNotificationBehavior.RequesterNotifications) Output only. Requester email notifications. |
| `admin_notifications`     | [`AdminNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.EmailNotificationSettings.CustomNotificationBehavior.AdminNotifications) Output only. Admin email notifications.             |
| `approver_notifications`  | [`ApproverNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.FetchEffectiveSettingsResponse.EmailNotificationSettings.CustomNotificationBehavior.ApproverNotifications) Output only. Approver email notifications.    |

## AdminNotifications

Email notifications specific to Admins.

| Fields                              |                                                                           |
|-------------------------------------|---------------------------------------------------------------------------|
| `notify_grant_activated`            | `bool` Output only. Notification delivery for grant activated.            |
| `notify_grant_ended`                | `bool` Output only. Notification delivery for grant ended.                |
| `notify_grant_externally_modified`  | `bool` Output only. Notification delivery for grant externally modified.  |
| `notify_grant_activation_failed`    | `bool` Output only. Notification delivery for grant activation failed.    |
| `notify_grant_activation_scheduled` | `bool` Output only. Notification delivery for grant activation scheduled. |

## ApproverNotifications

Email notifications specific to Approvers.

| Fields                    |                                                                 |
|---------------------------|-----------------------------------------------------------------|
| `notify_pending_approval` | `bool` Output only. Notification delivery for pending approval. |

## RequesterNotifications

Email notifications specific to Requesters.

| Fields                              |                                                                           |
|-------------------------------------|---------------------------------------------------------------------------|
| `notify_entitlement_assigned`       | `bool` Output only. Notification delivery for entitlement assigned.       |
| `notify_grant_activated`            | `bool` Output only. Notification delivery for grant activated.            |
| `notify_grant_denied`               | `bool` Output only. Notification delivery for grant denied.               |
| `notify_grant_expired`              | `bool` Output only. Notification delivery for grant request expired.      |
| `notify_grant_ended`                | `bool` Output only. Notification delivery for grant ended.                |
| `notify_grant_revoked`              | `bool` Output only. Notification delivery for grant revoked.              |
| `notify_grant_externally_modified`  | `bool` Output only. Notification delivery for grant externally modified.  |
| `notify_grant_activation_failed`    | `bool` Output only. Notification delivery for grant activation failed.    |
| `notify_grant_activation_scheduled` | `bool` Output only. Notification delivery for grant activation scheduled. |

## DisableAllNotifications

This type has no fields.

This option indicates that all email notifications are disabled.

## ServiceAccountApproverSettings

This controls whether service accounts are allowed to approve grants or can be designated as approvers within PAM entitlements.

| Fields    |                                                                                                                                                                                                                                                  |
|-----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `enabled` | `bool` Output only. Indicates whether service account is allowed to grant approvals.                                                                                                                                                             |
| `source`  | `string` Output only. The resource from which the service account approver setting is inherited. This field remains empty if the setting is not defined at either the parent or resource level, in which case PAM's default behavior is applied. |

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

## GetSettingsRequest

Request message for `GetSettings` method.

| Fields |                                                                     |
|--------|---------------------------------------------------------------------|
| `name` | `string` Required. The name of the settings resource to be fetched. |

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
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Justification"><code>Justification</code></a></p>
<p>Optional. Justification of why this access is needed.</p></td>
</tr>
<tr class="odd">
<td><code>state</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.State"><code>State</code></a></p>
<p>Output only. Current state of this grant.</p></td>
</tr>
<tr class="even">
<td><code>timeline</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline"><code>Timeline</code></a></p>
<p>Output only. Timeline of this grant.</p></td>
</tr>
<tr class="odd">
<td><code>privileged_access</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccess"><code>PrivilegedAccess</code></a></p>
<p>Output only. The access that would be granted by this grant.</p></td>
</tr>
<tr class="even">
<td><code>requested_privileged_access[]</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.RequestedPrivilegedAccess"><code>RequestedPrivilegedAccess</code></a></p>
<p>Optional. The accesses requested to be granted by this grant.</p></td>
</tr>
<tr class="odd">
<td><code>audit_trail</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.AuditTrail"><code>AuditTrail</code></a></p>
<p>Output only. Audit trail of access provided by this grant. If unspecified then access was never granted.</p></td>
</tr>
<tr class="even">
<td><code>additional_email_recipients[]</code></td>
<td><p><code>string</code></p>
<p>Optional. Additional email addresses to notify for all the actions performed on the grant.</p></td>
</tr>
<tr class="odd">
<td><code>externally_modified</code></td>
<td><p><code>bool</code></p>
<p>Output only. Flag set by the PAM system to indicate that policy bindings made by this grant have been modified from outside PAM.</p>
<p>After it is set, this flag remains set forever irrespective of the grant state. A <code>true</code> value here indicates that PAM no longer has any certainty on the access a user has because of this grant.</p></td>
</tr>
<tr class="even">
<td><code>activation_trigger</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.ActivationTrigger"><code>ActivationTrigger</code></a></p>
<p>Optional. The activation trigger for this grant. This field being absent indicates default behavior for the grant, that is, the grant will get activated as soon as the required number of approvals are received or, if approvals are not required, as soon as the grant is created.</p></td>
</tr>
</tbody>
</table>

## ActivationTrigger

ActivationTrigger represents the different possible activation triggers for the grant.

| Fields                                                                                                                                                                                           |                                                                                                                                          |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `activation_trigger` . A grant can have one of the valid activation triggers if it follows a non-default activation behavior. `activation_trigger` can be only one of the following: |                                                                                                                                          |
| `requested_activation_time`                                                                                                                                                                      | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) A specific time at which the access should be granted. |

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

| Fields     |                                                                                                                                                                                                                                                                                                                                                                                                                  |
|------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `events[]` | [`Event`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event) Output only. The events that have occurred on this grant. This list contains entries in the same order as they occurred. The first entry is always be of type `Requested` and there is always at least one entry in this array. |

## Event

A single operation on the grant.

| Fields                                                          |                                                                                                                                                                                                                                                                                           |
|-----------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `event_time`                                                    | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time (as recorded at server) when this event occurred.                                                                                                                                 |
| Union field `event` . `event` can be only one of the following: |                                                                                                                                                                                                                                                                                           |
| `requested`                                                     | [`Requested`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Requested) The grant was requested.                                                                   |
| `approved`                                                      | [`Approved`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Approved) The grant was approved.                                                                      |
| `denied`                                                        | [`Denied`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Denied) The grant was denied.                                                                            |
| `revoked`                                                       | [`Revoked`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Revoked) The grant was revoked.                                                                         |
| `scheduled`                                                     | [`Scheduled`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Scheduled) The grant has been scheduled to give access.                                               |
| `activated`                                                     | [`Activated`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Activated) The grant was successfully activated to give access.                                       |
| `activation_failed`                                             | [`ActivationFailed`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.ActivationFailed) There was a non-retriable error while trying to give access.                 |
| `expired`                                                       | [`Expired`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Expired) The approval workflow did not complete in the necessary duration, and so the grant is expired. |
| `ended`                                                         | [`Ended`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Ended) Access given by the grant ended automatically as the approved duration was over.                   |
| `externally_modified`                                           | [`ExternallyModified`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.ExternallyModified) The policy bindings made by grant have been modified outside of PAM.     |
| `withdrawn`                                                     | [`Withdrawn`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant.Timeline.Event.Withdrawn) The grant was withdrawn.                                                                   |

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

| Fields    |                                                                                    |
|-----------|------------------------------------------------------------------------------------|
| `reason`  | `string` Output only. The reason provided by the approver for approving the grant. |
| `actor`   | `string` Output only. Username of the user who approved the grant.                 |
| `step_id` | `string` Output only. The ID of the approval workflow step that was approved.      |

## Denied

An event representing that the grant was denied.

| Fields    |                                                                                  |
|-----------|----------------------------------------------------------------------------------|
| `reason`  | `string` Output only. The reason provided by the approver for denying the grant. |
| `actor`   | `string` Output only. Username of the user who denied the grant.                 |
| `step_id` | `string` Output only. The ID of the approval workflow step that was denied.      |

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

| Fields            |                                                                                                                                                                                                         |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `entitlements[]`  | [`Entitlement`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement) The list of entitlements. |
| `next_page_token` | `string` A token identifying a page of results the server should return.                                                                                                                                |
| `unreachable[]`   | `string` Locations that could not be reached.                                                                                                                                                           |

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

| Fields            |                                                                                                                                                                                       |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `grants[]`        | [`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant) The list of grants. |
| `next_page_token` | `string` A token identifying a page of results the server should return.                                                                                                              |
| `unreachable[]`   | `string` Locations that could not be reached.                                                                                                                                         |

## ManualApprovals

A manual approval workflow where users who are designated as approvers need to call the `ApproveGrant` / `DenyGrant` APIs for a grant. The workflow can consist of multiple serial steps where each step defines who can act as approver in that step and how many of those users should approve before the workflow moves to the next step.

This can be used to create approval workflows such as:

- Require an approval from any user in a group G.
- Require an approval from any k number of users from a Group G.
- Require an approval from any user in a group G and then from a user U.

A single user might be part of the `approvers` ACL for multiple steps in this workflow, but they can only approve once and that approval is only considered to satisfy the approval step at which it was granted.

| Fields                           |                                                                                                                                                                                                                                                                                                                            |
|----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `require_approver_justification` | `bool` Optional. Do the approvers need to provide a justification for their actions?                                                                                                                                                                                                                                       |
| `steps[]`                        | [`Step`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.ManualApprovals.Step) Optional. List of approval steps in this workflow. These steps are followed in the specified order sequentially. Only 1 step is supported. |

## Step

Step represents a logical step in a manual approval workflow.

| Fields                        |                                                                                                                                                                                                                                                                                              |
|-------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `approvers[]`                 | [`AccessControlEntry`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.AccessControlEntry) Optional. The potential set of approvers in this step. This list must contain at most one entry. |
| `approvals_needed`            | `int32` Required. How many users from the above list need to approve. If there aren't enough distinct users in the list, then the workflow indefinitely blocks. Should always be greater than 0. 1 is the only supported value.                                                              |
| `approver_email_recipients[]` | `string` Optional. Additional email addresses to be notified when a grant is pending approval.                                                                                                                                                                                               |
| `id`                          | `string` Output only. Step ID used to identify the step in the workflow.                                                                                                                                                                                                                     |

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

| Fields                                                                      |                                                                                                                                                                                                                                                 |
|-----------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `access_type` . `access_type` can be only one of the following: |                                                                                                                                                                                                                                                 |
| `gcp_iam_access`                                                            | [`GcpIamAccess`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccess.GcpIamAccess) Access to a Google Cloud resource through IAM. |

## GcpIamAccess

`GcpIamAccess` represents IAM based access control on a Google Cloud resource. Refer to <https://cloud.google.com/iam/docs> to understand more about IAM.

| Fields            |                                                                                                                                                                                                                                                                           |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resource_type`   | `string` Required. The type of this resource.                                                                                                                                                                                                                             |
| `resource`        | `string` Required. Name of the resource.                                                                                                                                                                                                                                  |
| `role_bindings[]` | [`RoleBinding`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccess.GcpIamAccess.RoleBinding) Required. Role bindings that are created on successful grant. |

## RoleBinding

IAM role bindings that are created after a successful grant.

| Fields                 |                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `role`                 | `string` Required. IAM role to be granted. <https://cloud.google.com/iam/docs/roles-overview> .                                                                                                                                                                                                                                                                                                                                    |
| `condition_expression` | `string` Optional. The expression field of the IAM condition to be associated with the role. If specified, a user with an active grant for this entitlement is able to access the resource only if this condition evaluates to true for their request. This field uses the same CEL format as IAM and supports all attributes that IAM supports, except tags. <https://cloud.google.com/iam/docs/conditions-overview#attributes> . |
| `id`                   | `string` Output only. The ID corresponding to this role binding in the policy binding. This will be unique within an entitlement across time. Gets re-generated each time the entitlement is updated.                                                                                                                                                                                                                              |

## RequestedPrivilegedAccess

Privileged access that is requested by a user via a grant.

| Fields                                                                                                                                                        |                                                                                                                                                                                                                                                          |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `access_type` . Type of access that is requested. Only GCP IAM based access is supported for now. `access_type` can be only one of the following: |                                                                                                                                                                                                                                                          |
| `gcp_iam_access`                                                                                                                                              | [`GcpIamAccess`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.RequestedPrivilegedAccess.GcpIamAccess) Access to a Google Cloud resource through IAM. |

## GcpIamAccess

`GcpIamAccess` represents IAM based access control on a Google Cloud resource. Refer to <https://cloud.google.com/iam/docs> to understand more about IAM.

| Fields            |                                                                                                                                                                                                                                                                                       |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resource_type`   | `string` Required. The type of this resource.                                                                                                                                                                                                                                         |
| `resource`        | `string` Required. Name of the resource.                                                                                                                                                                                                                                              |
| `role_bindings[]` | [`RoleBinding`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.RequestedPrivilegedAccess.GcpIamAccess.RoleBinding) Optional. Role bindings that are requested as part of the grant. |

## AccessRestrictions

AccessRestrictions represents a set of resources to further restrict the access to. This is used to get finer grained access as part of a grant. All restrictions are OR-ed with each other.

| Fields                     |                                                                                                                                                                          |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resource_names[]`         | `string` Optional. The resource names to restrict the access to. Follow <https://cloud.google.com/iam/docs/conditions-resource-attributes#resource-name> format.         |
| `resource_name_prefixes[]` | `string` Optional. The resource name prefixes to restrict the access to. Follow <https://cloud.google.com/iam/docs/conditions-resource-attributes#resource-name> format. |

## RoleBinding

IAM role bindings that are requested as part of the grant.

| Fields                             |                                                                                                                                                                                                                                                                                                                                                                                       |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `entitlement_role_binding_id`      | `string` Required. The role binding id of the role to be granted from the entitlement.                                                                                                                                                                                                                                                                                                |
| `access_restrictions`              | [`AccessRestrictions`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.RequestedPrivilegedAccess.GcpIamAccess.AccessRestrictions) Optional. The access restrictions to be applied to the role binding. This further restricts the access of this role binding to specific resources. |
| `role`                             | `string` Output only. The IAM role requested as part of the grant.                                                                                                                                                                                                                                                                                                                    |
| `entitlement_condition_expression` | `string` Output only. The IAM condition expression associated with the role at the time of grant request.                                                                                                                                                                                                                                                                             |

## RevokeGrantRequest

Request message for `RevokeGrant` method.

| Fields   |                                                                       |
|----------|-----------------------------------------------------------------------|
| `name`   | `string` Required. Name of the grant resource which is being revoked. |
| `reason` | `string` Optional. The reason for revoking this grant.                |

## SearchEntitlementsRequest

Request message for `SearchEntitlements` method.

| Fields               |                                                                                                                                                                                                                                                                                                    |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`             | `string` Required. The parent which owns the entitlement resources.                                                                                                                                                                                                                                |
| `caller_access_type` | [`CallerAccessType`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.SearchEntitlementsRequest.CallerAccessType) Required. Only entitlements where the calling user has this access are returned. |
| `filter`             | `string` Optional. Only entitlements matching this filter are returned in the response.                                                                                                                                                                                                            |
| `page_size`          | `int32` Optional. Requested page size. The server may return fewer items than requested. If unspecified, the server picks an appropriate default.                                                                                                                                                  |
| `page_token`         | `string` Optional. A token identifying a page of results the server should return.                                                                                                                                                                                                                 |

## CallerAccessType

Different types of access a user can have on the entitlement resource.

| Enums                            |                                                                            |
|----------------------------------|----------------------------------------------------------------------------|
| `CALLER_ACCESS_TYPE_UNSPECIFIED` | Unspecified access type.                                                   |
| `GRANT_REQUESTER`                | The user has access to create grants using this entitlement.               |
| `GRANT_APPROVER`                 | The user has access to approve/deny grants created under this entitlement. |

## SearchEntitlementsResponse

Response message for `SearchEntitlements` method.

| Fields            |                                                                                                                                                                                                         |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `entitlements[]`  | [`Entitlement`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement) The list of entitlements. |
| `next_page_token` | `string` A token identifying a page of results the server should return.                                                                                                                                |

## SearchGrantsRequest

Request message for `SearchGrants` method.

| Fields                |                                                                                                                                                                                                                                                                                                                                 |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`              | `string` Required. The parent which owns the grant resources.                                                                                                                                                                                                                                                                   |
| `caller_relationship` | [`CallerRelationshipType`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.SearchGrantsRequest.CallerRelationshipType) Required. Only grants which the caller is related to by this relationship are returned in the response. |
| `filter`              | `string` Optional. Only grants matching this filter are returned in the response.                                                                                                                                                                                                                                               |
| `page_size`           | `int32` Optional. Requested page size. The server may return fewer items than requested. If unspecified, server picks an appropriate default.                                                                                                                                                                                   |
| `page_token`          | `string` Optional. A token identifying a page of results the server should return.                                                                                                                                                                                                                                              |

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

| Fields            |                                                                                                                                                                                       |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `grants[]`        | [`Grant`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Grant) The list of grants. |
| `next_page_token` | `string` A token identifying a page of results the server should return.                                                                                                              |

## Settings

`Settings` resource defines the properties, applied directly to the resource or inherited through the hierarchy, to enable consistent, federated use of PAM.

The behavior is as follows: 1. If explicitly set to empty at the node level, PAM's default settings are applied for that node. 2. If not set at the node level, settings are inherited from the closest ancestor with a non-empty value. If none of the ancestors has the field set, PAM's default settings are applied. 3. If explicitly set to a non-empty value at the node level, the specified settings are applied for that node.

| Fields                              |                                                                                                                                                                                                                                                                                                                                   |
|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`                              | `string` Identifier. Name of the settings resource. Possible formats: projects/{project-id\|project-number}/locations/{location}/settings folders/{folder-number}/locations/{location}/settings organizations/{organization-number}/locations/{location}/settings                                                                 |
| `create_time`                       | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. Create timestamp.                                                                                                                                                                                                                  |
| `update_time`                       | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. Update timestamp.                                                                                                                                                                                                                  |
| `etag`                              | `string` Fingerprint for optimistic concurrency returned in the response of `GetSettings` . Must be provided in the requests to `UpdateSettings` . If the value provided does not match the value known to the server, ABORTED will be thrown, and the client should retry the read-modify-write cycle.                           |
| `service_account_approver_settings` | [`ServiceAccountApproverSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.ServiceAccountApproverSettings) Optional. This controls the node-level settings for allowing service accounts as approvers.          |
| `email_notification_settings`       | [`EmailNotificationSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings) Optional. `EmailNotificationSettings` defines node-wide email notification preferences for various PAM events. |

## EmailNotificationSettings

`EmailNotificationSettings` defines the node-wide email notification settings.

| Fields                                                                                                                                                                                                                                                                                                                                                                                                                                        |                                                                                                                                                                                                                                                                                    |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `notification_behavior` . Notification behavior. 1. If set to `DisableAllNotifications` , all notifications are disabled for the node. 2. If set to `CustomNotificationBehavior` , notifications are customized as per the specified settings. 3. If notification_behavior is not set (none of the options selected), PAM's default settings are applied for that node. `notification_behavior` can be only one of the following: |                                                                                                                                                                                                                                                                                    |
| `disable_all_notifications`                                                                                                                                                                                                                                                                                                                                                                                                                   | [`DisableAllNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.DisableAllNotifications) Disable all notifications.                |
| `custom_notification_behavior`                                                                                                                                                                                                                                                                                                                                                                                                                | [`CustomNotificationBehavior`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior) Granular settings of notifications. |

## CustomNotificationBehavior

`CustomNotificationBehavior` provides granular control over email notification delivery. Allows admins to selectively enable/disable notifications for specific events and specific personas.

| Fields                    |                                                                                                                                                                                                                                                                                                            |
|---------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `requester_notifications` | [`RequesterNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.RequesterNotifications) Optional. Requester email notifications. |
| `admin_notifications`     | [`AdminNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.AdminNotifications) Optional. Admin email notifications.             |
| `approver_notifications`  | [`ApproverNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.ApproverNotifications) Optional. Approver email notifications.    |

## AdminNotifications

Email notifications specific to Admins.

| Fields                       |                                                                                                                                                                                                                                                                                                                   |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `grant_activated`            | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant activated.            |
| `grant_ended`                | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant ended.                |
| `grant_externally_modified`  | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant externally modified.  |
| `grant_activation_failed`    | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant activation failed.    |
| `grant_activation_scheduled` | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant activation scheduled. |

## ApproverNotifications

Email notifications specific to Approvers.

| Fields             |                                                                                                                                                                                                                                                                                                         |
|--------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `pending_approval` | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for pending approval. |

## NotificationMode

`NotificationMode` represents the notification delivery setting.

| Enums                           |                                                                  |
|---------------------------------|------------------------------------------------------------------|
| `NOTIFICATION_MODE_UNSPECIFIED` | Default notification behavior following PAM's standard settings. |
| `ENABLED`                       | Notifications are enabled.                                       |
| `DISABLED`                      | Notifications are disabled.                                      |

## RequesterNotifications

Email notifications specific to Requesters.

| Fields                       |                                                                                                                                                                                                                                                                                                                   |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `entitlement_assigned`       | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for entitlement assigned.       |
| `grant_activated`            | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant activated.            |
| `grant_denied`               | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant denied.               |
| `grant_expired`              | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant request expired.      |
| `grant_ended`                | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant ended.                |
| `grant_revoked`              | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant revoked.              |
| `grant_externally_modified`  | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant externally modified.  |
| `grant_activation_failed`    | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant activation failed.    |
| `grant_activation_scheduled` | [`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings.EmailNotificationSettings.CustomNotificationBehavior.NotificationMode) Optional. Notification mode for grant activation scheduled. |

## DisableAllNotifications

This type has no fields.

This option indicates that all email notifications are disabled.

## ServiceAccountApproverSettings

This controls whether service accounts are allowed to approve grants or can be designated as approvers within PAM entitlements.

| Fields    |                                                                                   |
|-----------|-----------------------------------------------------------------------------------|
| `enabled` | `bool` Optional. Indicates whether service account is allowed to grant approvals. |

## UpdateEntitlementRequest

Message for updating an entitlement.

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `entitlement` | [`Entitlement`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Entitlement) Required. The entitlement resource that is updated.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `update_mask` | [`FieldMask`](https://protobuf.dev/reference/protobuf/google.protobuf/#field-mask) Required. The list of fields to update. A field is overwritten if, and only if, it is in the mask. Any immutable fields set in the mask are ignored by the server. Repeated fields and map fields are only allowed in the last position of a `paths` string and overwrite the existing values. Hence an update to a repeated field or a map should contain the entire list of values. The fields specified in the update_mask are relative to the resource and not to the request. (e.g. `MaxRequestDuration` ; *not* `entitlement.MaxRequestDuration` ) A value of '\*' for this field refers to full replacement of the resource. |

## UpdateSettingsRequest

Request message for `UpdateSettings` method.

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `settings`    | [`Settings`](https://docs.cloud.google.com/iam/docs/reference/pam/rpc/google.cloud.privilegedaccessmanager.v1beta#google.cloud.privilegedaccessmanager.v1beta.Settings) Required. The settings resource to be updated.                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `update_mask` | [`FieldMask`](https://protobuf.dev/reference/protobuf/google.protobuf/#field-mask) Required. The list of fields to update. A field is overwritten if, and only if, it is in the mask. Any immutable fields set in the mask are ignored by the server. Repeated fields and map fields are only allowed in the last position of a `paths` string and overwrite the existing values. Hence an update to a repeated field or a map should contain the entire list of values. The fields specified in the update_mask are relative to the resource and not to the request. A value of '\*' for this field refers to full replacement of the resource. |

## WithdrawGrantRequest

Request message for `WithdrawGrant` method.

| Fields |                                                                         |
|--------|-------------------------------------------------------------------------|
| `name` | `string` Required. Name of the grant resource which is being withdrawn. |
