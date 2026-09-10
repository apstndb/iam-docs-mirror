---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rpc
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rpc
title: Privileged Access Manager API
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

Privileged Access Manager (PAM) helps you to follow least privilege best practice to mitigate risks tied to privileged access misuse and abuse. You can shift from always-on standing privileges to on-demand access using time-bound and approval-based access elevations. IAM administrators specifically can use PAM to create entitlements that can grant temporary access to a specific resource scope. Requesters can explore eligible entitlements and request the access needed for their task, and approvers are notified when approvals require their attention. Streamlined workflows facilitated using PAM support several use cases, including the following:

  - Emergency access for incident responders

  - Time-boxed access for developers for critical deployment or maintenance

  - Temporary access for operators for data ingestion and audits

  - Temporary access to service accounts for automated tasks

## Service: privilegedaccessmanager.googleapis.com

The Service name `privilegedaccessmanager.googleapis.com` is needed to create RPC client stubs.

## `        google.cloud.location.Locations       `

Methods

`  GetLocation  `

Gets information about a location.

`  ListLocations  `

Lists information about the supported locations for this service.

## `        google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager       `

Methods

`  ApproveGrant  `

`ApproveGrant` is used to approve a grant.

`  CheckOnboardingStatus  `

`CheckOnboardingStatus` reports the onboarding status for a project, folder, or organization.

`  CreateEntitlement  `

Creates a new entitlement in a given project, folder, organization, and in a given location.

`  CreateGrant  `

Creates a grant in a given project, folder, or organization and location.

`  DeleteEntitlement  `

Deletes a single entitlement.

`  DenyGrant  `

`DenyGrant` is used to deny a grant.

`  GetEntitlement  `

Gets details of a single entitlement.

`  GetGrant  `

Get details of a single grant.

`  ListEntitlements  `

Lists the entitlements in a given project, folder, organization, and in a given location.

`  ListGrants  `

Lists grants for a given entitlement.

`  RevokeGrant  `

`RevokeGrant` is used to immediately revoke access for a grant.

`  SearchEntitlements  `

`SearchEntitlements` returns entitlements on which the caller has the specified access.

`  SearchGrants  `

`SearchGrants` returns grants that are related to the calling user in the specified way.

`  UpdateEntitlement  `

Updates the entitlement specified in the request.

## `        google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager       `

Methods

`  ApproveGrant  `

`ApproveGrant` is used to approve a grant.

`  CheckOnboardingStatus  `

`CheckOnboardingStatus` reports the onboarding status for a project, folder, or organization.

`  CreateEntitlement  `

Creates a new entitlement in a given project, folder, organization, and in a given location.

`  CreateGrant  `

Creates a grant in a given project, folder, or organization and location.

`  DeleteEntitlement  `

Deletes a single entitlement.

`  DenyGrant  `

`DenyGrant` is used to deny a grant.

`  FetchEffectiveSettings  `

`FetchEffectiveSettings` returns the effective PAM Settings for the given project, folder, or organization.

`  GetEntitlement  `

Gets details of a single entitlement.

`  GetGrant  `

Get details of a single grant.

`  GetSettings  `

`GetSettings` returns the PAM Settings for the given project, folder, or organization.

`  ListEntitlements  `

Lists the entitlements in a given project, folder, organization, and in a given location.

`  ListGrants  `

Lists grants for a given entitlement.

`  RevokeGrant  `

`RevokeGrant` is used to immediately revoke access for a grant.

`  SearchEntitlements  `

`SearchEntitlements` returns entitlements on which the caller has the specified access.

`  SearchGrants  `

`SearchGrants` returns grants that are related to the calling user in the specified way.

`  UpdateEntitlement  `

Updates the entitlement specified in the request.

`  UpdateSettings  `

`UpdateSettings` updates the PAM Settings resource specified in the request.

`  WithdrawGrant  `

`WithdrawGrant` is used to immediately withdraw the grant.

## `        google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager       `

Methods

`  ApproveGrant  `

`ApproveGrant` is used to approve a grant.

`  CheckOnboardingStatus  `

`CheckOnboardingStatus` reports the onboarding status for a project, folder, or organization.

`  CreateEntitlement  `

Creates a new entitlement in a given project, folder, organization, and in a given location.

`  CreateGrant  `

Creates a grant in a given project, folder, or organization and location.

`  DeleteEntitlement  `

Deletes a single entitlement.

`  DenyGrant  `

`DenyGrant` is used to deny a grant.

`  FetchEffectiveSettings  `

`FetchEffectiveSettings` returns the effective PAM Settings for the given project, folder, or organization.

`  GetEntitlement  `

Gets details of a single entitlement.

`  GetGrant  `

Get details of a single grant.

`  GetSettings  `

`GetSettings` returns the PAM Settings for the given project, folder, or organization.

`  ListEntitlements  `

Lists the entitlements in a given project, folder, organization, and in a given location.

`  ListGrants  `

Lists grants for a given entitlement.

`  RevokeGrant  `

`RevokeGrant` is used to immediately revoke access for a grant.

`  SearchEntitlements  `

`SearchEntitlements` returns entitlements on which the caller has the specified access.

`  SearchGrants  `

`SearchGrants` returns grants that are related to the calling user in the specified way.

`  UpdateEntitlement  `

Updates the entitlement specified in the request.

`  UpdateSettings  `

`UpdateSettings` updates the PAM Settings resource specified in the request.

`  WithdrawGrant  `

`WithdrawGrant` is used to immediately withdraw the grant.

## `        google.longrunning.Operations       `

Methods

`  CancelOperation  `

Starts asynchronous cancellation on a long-running operation.

`  DeleteOperation  `

Deletes a long-running operation.

`  GetOperation  `

Gets the latest state of a long-running operation.

`  ListOperations  `

Lists operations that match the specified filter in the request.

`  WaitOperation  `

Waits until the specified long-running operation is done or reaches at most a specified timeout, returning the latest state.
