---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest
title: Agent Identity API
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [REST Resource: v1beta.projects.locations](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest#v1beta.projects.locations)
  - [REST Resource: v1beta.projects.locations.accessSummaries](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest#v1beta.projects.locations.accessSummaries)
  - [REST Resource: v1beta.projects.locations.authProviders](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest#v1beta.projects.locations.authProviders)
  - [REST Resource: v1beta.projects.locations.authProviders.authorizations](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest#v1beta.projects.locations.authProviders.authorizations)
  - [REST Resource: v1.projects.locations](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest#v1.projects.locations)
  - [REST Resource: v1.projects.locations.accessSummaries](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest#v1.projects.locations.accessSummaries)
  - [REST Resource: v1.projects.locations.authProviders](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest#v1.projects.locations.authProviders)
  - [REST Resource: v1.projects.locations.authProviders.authorizations](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest#v1.projects.locations.authProviders.authorizations)

## Service: agentidentity.googleapis.com

To call this service, we recommend that you use the Google-provided [client libraries](https://cloud.google.com/apis/docs/client-libraries-explained) . If your application needs to use your own libraries to call this service, use the following information when you make the API requests.

### Discovery document

A [Discovery Document](https://developers.google.com/discovery/v1/reference/apis) is a machine-readable specification for describing and consuming REST APIs. It is used to build client libraries, IDE plugins, and other tools that interact with Google APIs. One service may provide multiple discovery documents. This service provides the following discovery documents:

  - <https://agentidentity.googleapis.com/$discovery/rest?version=v1>
  - <https://agentidentity.googleapis.com/$discovery/rest?version=v1beta>

### Service endpoint

A [service endpoint](https://cloud.google.com/apis/design/glossary#api_service_endpoint) is a base URL that specifies the network address of an API service. One service might have multiple service endpoints. This service has the following service endpoint and all URIs below are relative to this service endpoint:

  - `https://agentidentity.googleapis.com`

## REST Resource: [v1beta.projects.locations](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations)

Methods

`  get  `

`GET /v1beta/{name=projects/*/locations/*}`  
Gets information about a location.

`  list  `

`GET /v1beta/{name=projects/*}/locations`  
Lists information about the supported locations for this service.

## REST Resource: [v1beta.projects.locations.accessSummaries](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries)

Methods

`  get  `

`GET /v1beta/{name=projects/*/locations/*/accessSummaries/*}`  
Gets details of a single access summary.

`  list  `

`GET /v1beta/{parent=projects/*/locations/*}/accessSummaries`  
Lists access summaries in a given project and location.

## REST Resource: [v1beta.projects.locations.authProviders](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders)

Methods

`  create  `

`POST /v1beta/{parent=projects/*/locations/*}/authProviders`  
Creates a new auth provider in a given project and location.

`  delete  `

`DELETE /v1beta/{name=projects/*/locations/*/authProviders/*}`  
Deletes a single auth provider.

`  disable  `

`POST /v1beta/{name=projects/*/locations/*/authProviders/*}:disable`  
Disables a single auth provider.

`  enable  `

`POST /v1beta/{name=projects/*/locations/*/authProviders/*}:enable`  
Enables a single auth provider.

`  get  `

`GET /v1beta/{name=projects/*/locations/*/authProviders/*}`  
Gets details of a single auth provider.

`  getIamPolicy  `

`GET /v1beta/{resource=projects/*/locations/*/authProviders/*}:getIamPolicy`  
Gets the access control policy for a resource.

`  list  `

`GET /v1beta/{parent=projects/*/locations/*}/authProviders`  
Lists auth providers in a given project and location.

`  patch  `

`PATCH /v1beta/{authProvider.name=projects/*/locations/*/authProviders/*}`  
Updates the parameters of a single auth provider.

`  query  `

`GET /v1beta/{parent=projects/*/locations/*}/authProviders:query`  
Queries which auth providers are used by a given workload ID.

`  queryWorkloads  `

`GET /v1beta/{name=projects/*/locations/*/authProviders/*}:queryWorkloads`  
Queries which workloads are using a given auth provider.

`  revokeAuthorization  `

`POST /v1beta/{name=projects/*/locations/*/authProviders/*}:revokeAuthorization`  
Revokes all authorizations for a specific user on an auth provider.

`  setIamPolicy  `

`POST /v1beta/{resource=projects/*/locations/*/authProviders/*}:setIamPolicy`  
Sets the access control policy on the specified resource.

`  testIamPermissions  `

`POST /v1beta/{resource=projects/*/locations/*/authProviders/*}:testIamPermissions`  
Returns permissions that a caller has on the specified resource.

`  undelete  `

`POST /v1beta/{name=projects/*/locations/*/authProviders/*}:undelete`  
Undeletes a single auth provider.

## REST Resource: [v1beta.projects.locations.authProviders.authorizations](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders.authorizations)

Methods

`  delete  `

`DELETE /v1beta/{name=projects/*/locations/*/authProviders/*/authorizations/*}`  
Deletes a single authorization.

`  get  `

`GET /v1beta/{name=projects/*/locations/*/authProviders/*/authorizations/*}`  
Gets details of a single authorization.

`  list  `

`GET /v1beta/{parent=projects/*/locations/*/authProviders/*}/authorizations`  
Lists authorizations in a given project and location.

## REST Resource: [v1.projects.locations](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations)

Methods

`  get  `

`GET /v1/{name=projects/*/locations/*}`  
Gets information about a location.

`  list  `

`GET /v1/{name=projects/*}/locations`  
Lists information about the supported locations for this service.

## REST Resource: [v1.projects.locations.accessSummaries](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.accessSummaries)

Methods

`  get  `

`GET /v1/{name=projects/*/locations/*/accessSummaries/*}`  
Gets details of a single access summary.

`  list  `

`GET /v1/{parent=projects/*/locations/*}/accessSummaries`  
Lists access summaries in a given project and location.

## REST Resource: [v1.projects.locations.authProviders](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders)

Methods

`  create  `

`POST /v1/{parent=projects/*/locations/*}/authProviders`  
Creates a new auth provider in a given project and location.

`  delete  `

`DELETE /v1/{name=projects/*/locations/*/authProviders/*}`  
Deletes a single auth provider.

`  disable  `

`POST /v1/{name=projects/*/locations/*/authProviders/*}:disable`  
Disables a single auth provider.

`  enable  `

`POST /v1/{name=projects/*/locations/*/authProviders/*}:enable`  
Enables a single auth provider.

`  get  `

`GET /v1/{name=projects/*/locations/*/authProviders/*}`  
Gets details of a single auth provider.

`  getIamPolicy  `

`GET /v1/{resource=projects/*/locations/*/authProviders/*}:getIamPolicy`  
Gets the access control policy for a resource.

`  list  `

`GET /v1/{parent=projects/*/locations/*}/authProviders`  
Lists auth providers in a given project and location.

`  patch  `

`PATCH /v1/{authProvider.name=projects/*/locations/*/authProviders/*}`  
Updates the parameters of a single auth provider.

`  query  `

`GET /v1/{parent=projects/*/locations/*}/authProviders:query`  
Queries which auth providers are used by a given workload ID.

`  queryWorkloads  `

`GET /v1/{name=projects/*/locations/*/authProviders/*}:queryWorkloads`  
Queries which workloads are using a given auth provider.

`  revokeAuthorization  `

`POST /v1/{name=projects/*/locations/*/authProviders/*}:revokeAuthorization`  
Revokes all authorizations for a specific user on an auth provider.

`  setIamPolicy  `

`POST /v1/{resource=projects/*/locations/*/authProviders/*}:setIamPolicy`  
Sets the access control policy on the specified resource.

`  testIamPermissions  `

`POST /v1/{resource=projects/*/locations/*/authProviders/*}:testIamPermissions`  
Returns permissions that a caller has on the specified resource.

`  undelete  `

`POST /v1/{name=projects/*/locations/*/authProviders/*}:undelete`  
Undeletes a single auth provider.

## REST Resource: [v1.projects.locations.authProviders.authorizations](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations)

Methods

`  delete  `

`DELETE /v1/{name=projects/*/locations/*/authProviders/*/authorizations/*}`  
Deletes a single authorization.

`  get  `

`GET /v1/{name=projects/*/locations/*/authProviders/*/authorizations/*}`  
Gets details of a single authorization.

`  list  `

`GET /v1/{parent=projects/*/locations/*/authProviders/*}/authorizations`  
Lists authorizations in a given project and location.
