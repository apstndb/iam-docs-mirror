---
name: documents/docs.cloud.google.com/iam/docs/reference/credentials/rest
uri: https://docs.cloud.google.com/iam/docs/reference/credentials/rest
title: IAM Service Account Credentials API
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

Creates short-lived credentials for impersonating IAM service accounts. Disabling this API also disables the IAM API (iam.googleapis.com). However, enabling this API doesn't enable the IAM API.

  - [REST Resource: v1.locations.workforcePools](https://docs.cloud.google.com/iam/docs/reference/credentials/rest#v1.locations.workforcePools)
  - [REST Resource: v1.projects.locations.workloadIdentityPools](https://docs.cloud.google.com/iam/docs/reference/credentials/rest#v1.projects.locations.workloadIdentityPools)
  - [REST Resource: v1.projects.serviceAccounts](https://docs.cloud.google.com/iam/docs/reference/credentials/rest#v1.projects.serviceAccounts)

## Service: iamcredentials.googleapis.com

To call this service, we recommend that you use the Google-provided [client libraries](https://cloud.google.com/apis/docs/client-libraries-explained) . If your application needs to use your own libraries to call this service, use the following information when you make the API requests.

### Discovery document

A [Discovery Document](https://developers.google.com/discovery/v1/reference/apis) is a machine-readable specification for describing and consuming REST APIs. It is used to build client libraries, IDE plugins, and other tools that interact with Google APIs. One service may provide multiple discovery documents. This service provides the following discovery document:

  - <https://iamcredentials.googleapis.com/$discovery/rest?version=v1>

### Service endpoint

A [service endpoint](https://cloud.google.com/apis/design/glossary#api_service_endpoint) is a base URL that specifies the network address of an API service. One service might have multiple service endpoints. This service has the following service endpoint and all URIs below are relative to this service endpoint:

  - `https://iamcredentials.googleapis.com`

## REST Resource: [v1.locations.workforcePools](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/locations.workforcePools)

Methods

`  getAllowedLocations  `

`GET /v1/{name=locations/*/workforcePools/*}/allowedLocations`  
Returns the trust boundary info for a given workforce pool.

## REST Resource: [v1.projects.locations.workloadIdentityPools](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.locations.workloadIdentityPools)

Methods

`  getAllowedLocations  `

`GET /v1/{name=projects/*/locations/*/workloadIdentityPools/*}/allowedLocations`  
Returns the trust boundary info for a given workload identity pool.

## REST Resource: [v1.projects.serviceAccounts](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts)

Methods

`  generateAccessToken  `

`POST /v1/{name=projects/*/serviceAccounts/*}:generateAccessToken`  
Generates an OAuth 2.0 access token for a service account.

`  generateIdToken  `

`POST /v1/{name=projects/*/serviceAccounts/*}:generateIdToken`  
Generates an OpenID Connect ID token for a service account.

`  getAllowedLocations  `

`GET /v1/{name=projects/*/serviceAccounts/*}/allowedLocations`  
Returns the trust boundary info for a given service account.

`  signBlob  `

`POST /v1/{name=projects/*/serviceAccounts/*}:signBlob`  
Signs a blob using a service account's system-managed private key.

`  signJwt  `

`POST /v1/{name=projects/*/serviceAccounts/*}:signJwt`  
Signs a JWT using a service account's system-managed private key.
