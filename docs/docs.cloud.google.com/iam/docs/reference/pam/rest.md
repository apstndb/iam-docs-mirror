---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest
title: Privileged Access Manager API
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

Privileged Access Manager (PAM) helps you to follow least privilege best practice to mitigate risks tied to privileged access misuse and abuse. You can shift from always-on standing privileges to on-demand access using time-bound and approval-based access elevations. IAM administrators specifically can use PAM to create entitlements that can grant temporary access to a specific resource scope. Requesters can explore eligible entitlements and request the access needed for their task, and approvers are notified when approvals require their attention. Streamlined workflows facilitated using PAM support several use cases, including the following:

- Emergency access for incident responders

- Time-boxed access for developers for critical deployment or maintenance

- Temporary access for operators for data ingestion and audits

- Temporary access to service accounts for automated tasks

<!-- -->

- [REST Resource: v1beta.folders.locations](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1beta.folders.locations)
- [REST Resource: v1beta.folders.locations.entitlements](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1beta.folders.locations.entitlements)
- [REST Resource: v1beta.folders.locations.entitlements.grants](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1beta.folders.locations.entitlements.grants)
- [REST Resource: v1beta.folders.locations.operations](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1beta.folders.locations.operations)
- [REST Resource: v1beta.organizations.locations](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1beta.organizations.locations)
- [REST Resource: v1beta.organizations.locations.entitlements](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1beta.organizations.locations.entitlements)
- [REST Resource: v1beta.organizations.locations.entitlements.grants](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1beta.organizations.locations.entitlements.grants)
- [REST Resource: v1beta.organizations.locations.operations](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1beta.organizations.locations.operations)
- [REST Resource: v1beta.projects.locations](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1beta.projects.locations)
- [REST Resource: v1beta.projects.locations.entitlements](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1beta.projects.locations.entitlements)
- [REST Resource: v1beta.projects.locations.entitlements.grants](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1beta.projects.locations.entitlements.grants)
- [REST Resource: v1beta.projects.locations.operations](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1beta.projects.locations.operations)
- [REST Resource: v1.folders.locations](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1.folders.locations)
- [REST Resource: v1.folders.locations.entitlements](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1.folders.locations.entitlements)
- [REST Resource: v1.folders.locations.entitlements.grants](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1.folders.locations.entitlements.grants)
- [REST Resource: v1.folders.locations.operations](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1.folders.locations.operations)
- [REST Resource: v1.organizations.locations.entitlements](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1.organizations.locations.entitlements)
- [REST Resource: v1.organizations.locations.entitlements.grants](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1.organizations.locations.entitlements.grants)
- [REST Resource: v1.organizations.locations.operations](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1.organizations.locations.operations)
- [REST Resource: v1.projects.locations](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1.projects.locations)
- [REST Resource: v1.projects.locations.entitlements](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1.projects.locations.entitlements)
- [REST Resource: v1.projects.locations.entitlements.grants](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1.projects.locations.entitlements.grants)
- [REST Resource: v1.projects.locations.operations](https://docs.cloud.google.com/iam/docs/reference/pam/rest#v1.projects.locations.operations)

## Service: privilegedaccessmanager.googleapis.com

### Discovery document

A [Discovery Document](https://developers.google.com/discovery/v1/reference/apis) is a machine-readable specification for describing and consuming REST APIs. It is used to build client libraries, IDE plugins, and other tools that interact with Google APIs. One service may provide multiple discovery documents. This service provides the following discovery documents:

- <https://privilegedaccessmanager.googleapis.com/$discovery/rest?version=v1>
- <https://privilegedaccessmanager.googleapis.com/$discovery/rest?version=v1beta>

### Service endpoint

A [service endpoint](https://cloud.google.com/apis/design/glossary#api_service_endpoint) is a base URL that specifies the network address of an API service. One service might have multiple service endpoints. This service has the following service endpoint and all URIs below are relative to this service endpoint:

- `https://privilegedaccessmanager.googleapis.com`

## REST Resource: [v1beta.folders.locations](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations)

| Methods                                                                                                                               |                                                                                                                                                                                 |
|---------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`checkOnboardingStatus`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations/checkOnboardingStatus)   | `GET /v1beta/{parent=folders/*/locations/*}:checkOnboardingStatus` `CheckOnboardingStatus` reports the onboarding status for a project, folder, or organization.                |
| [`fetchEffectiveSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations/fetchEffectiveSettings) | `GET /v1beta/{parent=folders/*/locations/*}:fetchEffectiveSettings` `FetchEffectiveSettings` returns the effective PAM Settings for the given project, folder, or organization. |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations/get)                                       | `GET /v1beta/{name=folders/*/locations/*}` Gets information about a location.                                                                                                   |
| [`getSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations/getSettings)                       | `GET /v1beta/{name=folders/*/locations/*/settings}` `GetSettings` returns the PAM Settings for the given project, folder, or organization.                                      |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations/list)                                     | `GET /v1beta/{name=folders/*}/locations` Lists information about the supported locations for this service.                                                                      |
| [`updateSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations/updateSettings)                 | `PATCH /v1beta/{settings.name=folders/*/locations/*/settings}` `UpdateSettings` updates the PAM Settings resource specified in the request.                                     |

## REST Resource: [v1beta.folders.locations.entitlements](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements)

| Methods                                                                                                            |                                                                                                                                                          |
|--------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements/create) | `POST /v1beta/{parent=folders/*/locations/*}/entitlements` Creates a new entitlement in a given project, folder, organization, and in a given location.  |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements/delete) | `DELETE /v1beta/{name=folders/*/locations/*/entitlements/*}` Deletes a single entitlement.                                                               |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements/get)       | `GET /v1beta/{name=folders/*/locations/*/entitlements/*}` Gets details of a single entitlement.                                                          |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements/list)     | `GET /v1beta/{parent=folders/*/locations/*}/entitlements` Lists the entitlements in a given project, folder, organization, and in a given location.      |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements/patch)   | `PATCH /v1beta/{entitlement.name=folders/*/locations/*/entitlements/*}` Updates the entitlement specified in the request.                                |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements/search) | `GET /v1beta/{parent=folders/*/locations/*}/entitlements:search` `SearchEntitlements` returns entitlements on which the caller has the specified access. |

## REST Resource: [v1beta.folders.locations.entitlements.grants](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants)

| Methods                                                                                                                       |                                                                                                                                                                    |
|-------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`approve`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/approve)   | `POST /v1beta/{name=folders/*/locations/*/entitlements/*/grants/*}:approve` `ApproveGrant` is used to approve a grant.                                             |
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/create)     | `POST /v1beta/{parent=folders/*/locations/*/entitlements/*}/grants` Creates a grant in a given project, folder, or organization and location.                      |
| [`deny`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/deny)         | `POST /v1beta/{name=folders/*/locations/*/entitlements/*/grants/*}:deny` `DenyGrant` is used to deny a grant.                                                      |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/get)           | `GET /v1beta/{name=folders/*/locations/*/entitlements/*/grants/*}` Get details of a single grant.                                                                  |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/list)         | `GET /v1beta/{parent=folders/*/locations/*/entitlements/*}/grants` Lists grants for a given entitlement.                                                           |
| [`revoke`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/revoke)     | `POST /v1beta/{name=folders/*/locations/*/entitlements/*/grants/*}:revoke` `RevokeGrant` is used to immediately revoke access for a grant.                         |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/search)     | `GET /v1beta/{parent=folders/*/locations/*/entitlements/*}/grants:search` `SearchGrants` returns grants that are related to the calling user in the specified way. |
| [`withdraw`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/withdraw) | `POST /v1beta/{name=folders/*/locations/*/entitlements/*/grants/*}:withdraw` `WithdrawGrant` is used to immediately withdraw the grant.                            |

## REST Resource: [v1beta.folders.locations.operations](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.operations)

| Methods                                                                                                          |                                                                                                                        |
|------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.operations/delete) | `DELETE /v1beta/{name=folders/*/locations/*/operations/*}` Deletes a long-running operation.                           |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.operations/get)       | `GET /v1beta/{name=folders/*/locations/*/operations/*}` Gets the latest state of a long-running operation.             |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.operations/list)     | `GET /v1beta/{name=folders/*/locations/*}/operations` Lists operations that match the specified filter in the request. |

## REST Resource: [v1beta.organizations.locations](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations)

| Methods                                                                                                                                     |                                                                                                                                                                                       |
|---------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`checkOnboardingStatus`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/checkOnboardingStatus)   | `GET /v1beta/{parent=organizations/*/locations/*}:checkOnboardingStatus` `CheckOnboardingStatus` reports the onboarding status for a project, folder, or organization.                |
| [`fetchEffectiveSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/fetchEffectiveSettings) | `GET /v1beta/{parent=organizations/*/locations/*}:fetchEffectiveSettings` `FetchEffectiveSettings` returns the effective PAM Settings for the given project, folder, or organization. |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/get)                                       | `GET /v1beta/{name=organizations/*/locations/*}` Gets information about a location.                                                                                                   |
| [`getSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/getSettings)                       | `GET /v1beta/{name=organizations/*/locations/*/settings}` `GetSettings` returns the PAM Settings for the given project, folder, or organization.                                      |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/list)                                     | `GET /v1beta/{name=organizations/*}/locations` Lists information about the supported locations for this service.                                                                      |
| [`updateSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/updateSettings)                 | `PATCH /v1beta/{settings.name=organizations/*/locations/*/settings}` `UpdateSettings` updates the PAM Settings resource specified in the request.                                     |

## REST Resource: [v1beta.organizations.locations.entitlements](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements)

| Methods                                                                                                                  |                                                                                                                                                                |
|--------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/create) | `POST /v1beta/{parent=organizations/*/locations/*}/entitlements` Creates a new entitlement in a given project, folder, organization, and in a given location.  |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete) | `DELETE /v1beta/{name=organizations/*/locations/*/entitlements/*}` Deletes a single entitlement.                                                               |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/get)       | `GET /v1beta/{name=organizations/*/locations/*/entitlements/*}` Gets details of a single entitlement.                                                          |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/list)     | `GET /v1beta/{parent=organizations/*/locations/*}/entitlements` Lists the entitlements in a given project, folder, organization, and in a given location.      |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/patch)   | `PATCH /v1beta/{entitlement.name=organizations/*/locations/*/entitlements/*}` Updates the entitlement specified in the request.                                |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/search) | `GET /v1beta/{parent=organizations/*/locations/*}/entitlements:search` `SearchEntitlements` returns entitlements on which the caller has the specified access. |

## REST Resource: [v1beta.organizations.locations.entitlements.grants](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements.grants)

| Methods                                                                                                                             |                                                                                                                                                                          |
|-------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`approve`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements.grants/approve)   | `POST /v1beta/{name=organizations/*/locations/*/entitlements/*/grants/*}:approve` `ApproveGrant` is used to approve a grant.                                             |
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements.grants/create)     | `POST /v1beta/{parent=organizations/*/locations/*/entitlements/*}/grants` Creates a grant in a given project, folder, or organization and location.                      |
| [`deny`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements.grants/deny)         | `POST /v1beta/{name=organizations/*/locations/*/entitlements/*/grants/*}:deny` `DenyGrant` is used to deny a grant.                                                      |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements.grants/get)           | `GET /v1beta/{name=organizations/*/locations/*/entitlements/*/grants/*}` Get details of a single grant.                                                                  |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements.grants/list)         | `GET /v1beta/{parent=organizations/*/locations/*/entitlements/*}/grants` Lists grants for a given entitlement.                                                           |
| [`revoke`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements.grants/revoke)     | `POST /v1beta/{name=organizations/*/locations/*/entitlements/*/grants/*}:revoke` `RevokeGrant` is used to immediately revoke access for a grant.                         |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements.grants/search)     | `GET /v1beta/{parent=organizations/*/locations/*/entitlements/*}/grants:search` `SearchGrants` returns grants that are related to the calling user in the specified way. |
| [`withdraw`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements.grants/withdraw) | `POST /v1beta/{name=organizations/*/locations/*/entitlements/*/grants/*}:withdraw` `WithdrawGrant` is used to immediately withdraw the grant.                            |

## REST Resource: [v1beta.organizations.locations.operations](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.operations)

| Methods                                                                                                                |                                                                                                                              |
|------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.operations/delete) | `DELETE /v1beta/{name=organizations/*/locations/*/operations/*}` Deletes a long-running operation.                           |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.operations/get)       | `GET /v1beta/{name=organizations/*/locations/*/operations/*}` Gets the latest state of a long-running operation.             |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.operations/list)     | `GET /v1beta/{name=organizations/*/locations/*}/operations` Lists operations that match the specified filter in the request. |

## REST Resource: [v1beta.projects.locations](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations)

| Methods                                                                                                                                |                                                                                                                                                                                  |
|----------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`checkOnboardingStatus`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/checkOnboardingStatus)   | `GET /v1beta/{parent=projects/*/locations/*}:checkOnboardingStatus` `CheckOnboardingStatus` reports the onboarding status for a project, folder, or organization.                |
| [`fetchEffectiveSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/fetchEffectiveSettings) | `GET /v1beta/{parent=projects/*/locations/*}:fetchEffectiveSettings` `FetchEffectiveSettings` returns the effective PAM Settings for the given project, folder, or organization. |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/get)                                       | `GET /v1beta/{name=projects/*/locations/*}` Gets information about a location.                                                                                                   |
| [`getSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/getSettings)                       | `GET /v1beta/{name=projects/*/locations/*/settings}` `GetSettings` returns the PAM Settings for the given project, folder, or organization.                                      |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/list)                                     | `GET /v1beta/{name=projects/*}/locations` Lists information about the supported locations for this service.                                                                      |
| [`updateSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations/updateSettings)                 | `PATCH /v1beta/{settings.name=projects/*/locations/*/settings}` `UpdateSettings` updates the PAM Settings resource specified in the request.                                     |

## REST Resource: [v1beta.projects.locations.entitlements](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements)

| Methods                                                                                                             |                                                                                                                                                           |
|---------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/create) | `POST /v1beta/{parent=projects/*/locations/*}/entitlements` Creates a new entitlement in a given project, folder, organization, and in a given location.  |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/delete) | `DELETE /v1beta/{name=projects/*/locations/*/entitlements/*}` Deletes a single entitlement.                                                               |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/get)       | `GET /v1beta/{name=projects/*/locations/*/entitlements/*}` Gets details of a single entitlement.                                                          |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/list)     | `GET /v1beta/{parent=projects/*/locations/*}/entitlements` Lists the entitlements in a given project, folder, organization, and in a given location.      |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/patch)   | `PATCH /v1beta/{entitlement.name=projects/*/locations/*/entitlements/*}` Updates the entitlement specified in the request.                                |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements/search) | `GET /v1beta/{parent=projects/*/locations/*}/entitlements:search` `SearchEntitlements` returns entitlements on which the caller has the specified access. |

## REST Resource: [v1beta.projects.locations.entitlements.grants](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants)

| Methods                                                                                                                        |                                                                                                                                                                     |
|--------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`approve`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/approve)   | `POST /v1beta/{name=projects/*/locations/*/entitlements/*/grants/*}:approve` `ApproveGrant` is used to approve a grant.                                             |
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/create)     | `POST /v1beta/{parent=projects/*/locations/*/entitlements/*}/grants` Creates a grant in a given project, folder, or organization and location.                      |
| [`deny`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/deny)         | `POST /v1beta/{name=projects/*/locations/*/entitlements/*/grants/*}:deny` `DenyGrant` is used to deny a grant.                                                      |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/get)           | `GET /v1beta/{name=projects/*/locations/*/entitlements/*/grants/*}` Get details of a single grant.                                                                  |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/list)         | `GET /v1beta/{parent=projects/*/locations/*/entitlements/*}/grants` Lists grants for a given entitlement.                                                           |
| [`revoke`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/revoke)     | `POST /v1beta/{name=projects/*/locations/*/entitlements/*/grants/*}:revoke` `RevokeGrant` is used to immediately revoke access for a grant.                         |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/search)     | `GET /v1beta/{parent=projects/*/locations/*/entitlements/*}/grants:search` `SearchGrants` returns grants that are related to the calling user in the specified way. |
| [`withdraw`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/withdraw) | `POST /v1beta/{name=projects/*/locations/*/entitlements/*/grants/*}:withdraw` `WithdrawGrant` is used to immediately withdraw the grant.                            |

## REST Resource: [v1beta.projects.locations.operations](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.operations)

| Methods                                                                                                           |                                                                                                                         |
|-------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.operations/delete) | `DELETE /v1beta/{name=projects/*/locations/*/operations/*}` Deletes a long-running operation.                           |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.operations/get)       | `GET /v1beta/{name=projects/*/locations/*/operations/*}` Gets the latest state of a long-running operation.             |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.operations/list)     | `GET /v1beta/{name=projects/*/locations/*}/operations` Lists operations that match the specified filter in the request. |

## REST Resource: [v1.folders.locations](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations)

| Methods                                                                                                                         |                                                                                                                                                              |
|---------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`checkOnboardingStatus`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/checkOnboardingStatus) | `GET /v1/{parent=folders/*/locations/*}:checkOnboardingStatus` `CheckOnboardingStatus` reports the onboarding status for a project, folder, or organization. |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/get)                                     | `GET /v1/{name=folders/*/locations/*}` Gets information about a location.                                                                                    |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations/list)                                   | `GET /v1/{name=folders/*}/locations` Lists information about the supported locations for this service.                                                       |

## REST Resource: [v1.folders.locations.entitlements](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements)

| Methods                                                                                                        |                                                                                                                                                      |
|----------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/create) | `POST /v1/{parent=folders/*/locations/*}/entitlements` Creates a new entitlement in a given project, folder, organization, and in a given location.  |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/delete) | `DELETE /v1/{name=folders/*/locations/*/entitlements/*}` Deletes a single entitlement.                                                               |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/get)       | `GET /v1/{name=folders/*/locations/*/entitlements/*}` Gets details of a single entitlement.                                                          |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/list)     | `GET /v1/{parent=folders/*/locations/*}/entitlements` Lists the entitlements in a given project, folder, organization, and in a given location.      |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/patch)   | `PATCH /v1/{entitlement.name=folders/*/locations/*/entitlements/*}` Updates the entitlement specified in the request.                                |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/search) | `GET /v1/{parent=folders/*/locations/*}/entitlements:search` `SearchEntitlements` returns entitlements on which the caller has the specified access. |

## REST Resource: [v1.folders.locations.entitlements.grants](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants)

| Methods                                                                                                                 |                                                                                                                                                                |
|-------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`approve`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants/approve) | `POST /v1/{name=folders/*/locations/*/entitlements/*/grants/*}:approve` `ApproveGrant` is used to approve a grant.                                             |
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants/create)   | `POST /v1/{parent=folders/*/locations/*/entitlements/*}/grants` Creates a grant in a given project, folder, or organization and location.                      |
| [`deny`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants/deny)       | `POST /v1/{name=folders/*/locations/*/entitlements/*/grants/*}:deny` `DenyGrant` is used to deny a grant.                                                      |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants/get)         | `GET /v1/{name=folders/*/locations/*/entitlements/*/grants/*}` Get details of a single grant.                                                                  |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants/list)       | `GET /v1/{parent=folders/*/locations/*/entitlements/*}/grants` Lists grants for a given entitlement.                                                           |
| [`revoke`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants/revoke)   | `POST /v1/{name=folders/*/locations/*/entitlements/*/grants/*}:revoke` `RevokeGrant` is used to immediately revoke access for a grant.                         |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements.grants/search)   | `GET /v1/{parent=folders/*/locations/*/entitlements/*}/grants:search` `SearchGrants` returns grants that are related to the calling user in the specified way. |

## REST Resource: [v1.folders.locations.operations](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.operations)

| Methods                                                                                                      |                                                                                                                    |
|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.operations/delete) | `DELETE /v1/{name=folders/*/locations/*/operations/*}` Deletes a long-running operation.                           |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.operations/get)       | `GET /v1/{name=folders/*/locations/*/operations/*}` Gets the latest state of a long-running operation.             |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.operations/list)     | `GET /v1/{name=folders/*/locations/*}/operations` Lists operations that match the specified filter in the request. |

## REST Resource: [v1.organizations.locations](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations)

| Methods                                                                                                                               |                                                                                                                                                                    |
|---------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`checkOnboardingStatus`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations/checkOnboardingStatus) | `GET /v1/{parent=organizations/*/locations/*}:checkOnboardingStatus` `CheckOnboardingStatus` reports the onboarding status for a project, folder, or organization. |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations/get)                                     | `GET /v1/{name=organizations/*/locations/*}` Gets information about a location.                                                                                    |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations/list)                                   | `GET /v1/{name=organizations/*}/locations` Lists information about the supported locations for this service.                                                       |

## REST Resource: [v1.organizations.locations.entitlements](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements)

| Methods                                                                                                              |                                                                                                                                                            |
|----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/create) | `POST /v1/{parent=organizations/*/locations/*}/entitlements` Creates a new entitlement in a given project, folder, organization, and in a given location.  |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/delete) | `DELETE /v1/{name=organizations/*/locations/*/entitlements/*}` Deletes a single entitlement.                                                               |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/get)       | `GET /v1/{name=organizations/*/locations/*/entitlements/*}` Gets details of a single entitlement.                                                          |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/list)     | `GET /v1/{parent=organizations/*/locations/*}/entitlements` Lists the entitlements in a given project, folder, organization, and in a given location.      |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/patch)   | `PATCH /v1/{entitlement.name=organizations/*/locations/*/entitlements/*}` Updates the entitlement specified in the request.                                |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements/search) | `GET /v1/{parent=organizations/*/locations/*}/entitlements:search` `SearchEntitlements` returns entitlements on which the caller has the specified access. |

## REST Resource: [v1.organizations.locations.entitlements.grants](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements.grants)

| Methods                                                                                                                       |                                                                                                                                                                      |
|-------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`approve`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements.grants/approve) | `POST /v1/{name=organizations/*/locations/*/entitlements/*/grants/*}:approve` `ApproveGrant` is used to approve a grant.                                             |
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements.grants/create)   | `POST /v1/{parent=organizations/*/locations/*/entitlements/*}/grants` Creates a grant in a given project, folder, or organization and location.                      |
| [`deny`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements.grants/deny)       | `POST /v1/{name=organizations/*/locations/*/entitlements/*/grants/*}:deny` `DenyGrant` is used to deny a grant.                                                      |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements.grants/get)         | `GET /v1/{name=organizations/*/locations/*/entitlements/*/grants/*}` Get details of a single grant.                                                                  |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements.grants/list)       | `GET /v1/{parent=organizations/*/locations/*/entitlements/*}/grants` Lists grants for a given entitlement.                                                           |
| [`revoke`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements.grants/revoke)   | `POST /v1/{name=organizations/*/locations/*/entitlements/*/grants/*}:revoke` `RevokeGrant` is used to immediately revoke access for a grant.                         |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.entitlements.grants/search)   | `GET /v1/{parent=organizations/*/locations/*/entitlements/*}/grants:search` `SearchGrants` returns grants that are related to the calling user in the specified way. |

## REST Resource: [v1.organizations.locations.operations](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations)

| Methods                                                                                                            |                                                                                                                          |
|--------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/delete) | `DELETE /v1/{name=organizations/*/locations/*/operations/*}` Deletes a long-running operation.                           |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/get)       | `GET /v1/{name=organizations/*/locations/*/operations/*}` Gets the latest state of a long-running operation.             |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/list)     | `GET /v1/{name=organizations/*/locations/*}/operations` Lists operations that match the specified filter in the request. |

## REST Resource: [v1.projects.locations](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations)

| Methods                                                                                                                          |                                                                                                                                                               |
|----------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`checkOnboardingStatus`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations/checkOnboardingStatus) | `GET /v1/{parent=projects/*/locations/*}:checkOnboardingStatus` `CheckOnboardingStatus` reports the onboarding status for a project, folder, or organization. |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations/get)                                     | `GET /v1/{name=projects/*/locations/*}` Gets information about a location.                                                                                    |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations/list)                                   | `GET /v1/{name=projects/*}/locations` Lists information about the supported locations for this service.                                                       |

## REST Resource: [v1.projects.locations.entitlements](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements)

| Methods                                                                                                         |                                                                                                                                                       |
|-----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/create) | `POST /v1/{parent=projects/*/locations/*}/entitlements` Creates a new entitlement in a given project, folder, organization, and in a given location.  |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/delete) | `DELETE /v1/{name=projects/*/locations/*/entitlements/*}` Deletes a single entitlement.                                                               |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/get)       | `GET /v1/{name=projects/*/locations/*/entitlements/*}` Gets details of a single entitlement.                                                          |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/list)     | `GET /v1/{parent=projects/*/locations/*}/entitlements` Lists the entitlements in a given project, folder, organization, and in a given location.      |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/patch)   | `PATCH /v1/{entitlement.name=projects/*/locations/*/entitlements/*}` Updates the entitlement specified in the request.                                |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/search) | `GET /v1/{parent=projects/*/locations/*}/entitlements:search` `SearchEntitlements` returns entitlements on which the caller has the specified access. |

## REST Resource: [v1.projects.locations.entitlements.grants](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements.grants)

| Methods                                                                                                                  |                                                                                                                                                                 |
|--------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`approve`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements.grants/approve) | `POST /v1/{name=projects/*/locations/*/entitlements/*/grants/*}:approve` `ApproveGrant` is used to approve a grant.                                             |
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements.grants/create)   | `POST /v1/{parent=projects/*/locations/*/entitlements/*}/grants` Creates a grant in a given project, folder, or organization and location.                      |
| [`deny`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements.grants/deny)       | `POST /v1/{name=projects/*/locations/*/entitlements/*/grants/*}:deny` `DenyGrant` is used to deny a grant.                                                      |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements.grants/get)         | `GET /v1/{name=projects/*/locations/*/entitlements/*/grants/*}` Get details of a single grant.                                                                  |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements.grants/list)       | `GET /v1/{parent=projects/*/locations/*/entitlements/*}/grants` Lists grants for a given entitlement.                                                           |
| [`revoke`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements.grants/revoke)   | `POST /v1/{name=projects/*/locations/*/entitlements/*/grants/*}:revoke` `RevokeGrant` is used to immediately revoke access for a grant.                         |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements.grants/search)   | `GET /v1/{parent=projects/*/locations/*/entitlements/*}/grants:search` `SearchGrants` returns grants that are related to the calling user in the specified way. |

## REST Resource: [v1.projects.locations.operations](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.operations)

| Methods                                                                                                       |                                                                                                                     |
|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.operations/delete) | `DELETE /v1/{name=projects/*/locations/*/operations/*}` Deletes a long-running operation.                           |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.operations/get)       | `GET /v1/{name=projects/*/locations/*/operations/*}` Gets the latest state of a long-running operation.             |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.operations/list)     | `GET /v1/{name=projects/*/locations/*}/operations` Lists operations that match the specified filter in the request. |
