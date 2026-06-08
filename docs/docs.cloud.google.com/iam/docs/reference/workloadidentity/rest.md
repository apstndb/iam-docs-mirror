---
name: documents/docs.cloud.google.com/iam/docs/reference/workloadidentity/rest
uri: https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest
title: Workload Identity API
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [REST Resource: v1.folders.locations](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest#v1.folders.locations)
  - [REST Resource: v1.folders.locations.operations](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest#v1.folders.locations.operations)
  - [REST Resource: v1.folders.locations.serviceProducers](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest#v1.folders.locations.serviceProducers)
  - [REST Resource: v1.organizations.locations](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest#v1.organizations.locations)
  - [REST Resource: v1.organizations.locations.operations](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest#v1.organizations.locations.operations)
  - [REST Resource: v1.organizations.locations.serviceProducers](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest#v1.organizations.locations.serviceProducers)
  - [REST Resource: v1.projects.locations](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest#v1.projects.locations)
  - [REST Resource: v1.projects.locations.operations](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest#v1.projects.locations.operations)
  - [REST Resource: v1.projects.locations.serviceProducers](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest#v1.projects.locations.serviceProducers)

## Service: workloadidentity.googleapis.com

To call this service, we recommend that you use the Google-provided [client libraries](https://cloud.google.com/apis/docs/client-libraries-explained) . If your application needs to use your own libraries to call this service, use the following information when you make the API requests.

### Discovery document

A [Discovery Document](https://developers.google.com/discovery/v1/reference/apis) is a machine-readable specification for describing and consuming REST APIs. It is used to build client libraries, IDE plugins, and other tools that interact with Google APIs. One service may provide multiple discovery documents. This service provides the following discovery document:

  - <https://workloadidentity.googleapis.com/$discovery/rest?version=v1>

### Service endpoint

A [service endpoint](https://cloud.google.com/apis/design/glossary#api_service_endpoint) is a base URL that specifies the network address of an API service. One service might have multiple service endpoints. This service has the following service endpoint and all URIs below are relative to this service endpoint:

  - `https://workloadidentity.googleapis.com`

## REST Resource: [v1.folders.locations](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations)

Methods

`  get  `

`GET /v1/{name=folders/*/locations/*}`  
Gets information about a location.

`  list  `

`GET /v1/{name=folders/*}/locations`  
Lists information about the supported locations for this service.

## REST Resource: [v1.folders.locations.operations](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations.operations)

Methods

`  cancel  `

`POST /v1/{name=folders/*/locations/*/operations/*}:cancel`  
Starts asynchronous cancellation on a long-running operation.

`  delete  `

`DELETE /v1/{name=folders/*/locations/*/operations/*}`  
Deletes a long-running operation.

`  get  `

`GET /v1/{name=folders/*/locations/*/operations/*}`  
Gets the latest state of a long-running operation.

`  list  `

`GET /v1/{name=folders/*/locations/*}/operations`  
Lists operations that match the specified filter in the request.

## REST Resource: [v1.folders.locations.serviceProducers](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations.serviceProducers)

Methods

`  generateServiceAgents  `

`POST /v1/{parent=folders/*/locations/*/serviceProducers/*}:generateServiceAgents`  
Creates all service agents for a given resource, location and service producer.

## REST Resource: [v1.organizations.locations](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/organizations.locations)

Methods

`  get  `

`GET /v1/{name=organizations/*/locations/*}`  
Gets information about a location.

`  list  `

`GET /v1/{name=organizations/*}/locations`  
Lists information about the supported locations for this service.

## REST Resource: [v1.organizations.locations.operations](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/organizations.locations.operations)

Methods

`  cancel  `

`POST /v1/{name=organizations/*/locations/*/operations/*}:cancel`  
Starts asynchronous cancellation on a long-running operation.

`  delete  `

`DELETE /v1/{name=organizations/*/locations/*/operations/*}`  
Deletes a long-running operation.

`  get  `

`GET /v1/{name=organizations/*/locations/*/operations/*}`  
Gets the latest state of a long-running operation.

`  list  `

`GET /v1/{name=organizations/*/locations/*}/operations`  
Lists operations that match the specified filter in the request.

## REST Resource: [v1.organizations.locations.serviceProducers](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/organizations.locations.serviceProducers)

Methods

`  generateServiceAgents  `

`POST /v1/{parent=organizations/*/locations/*/serviceProducers/*}:generateServiceAgents`  
Creates all service agents for a given resource, location and service producer.

## REST Resource: [v1.projects.locations](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/projects.locations)

Methods

`  get  `

`GET /v1/{name=projects/*/locations/*}`  
Gets information about a location.

`  list  `

`GET /v1/{name=projects/*}/locations`  
Lists information about the supported locations for this service.

## REST Resource: [v1.projects.locations.operations](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/projects.locations.operations)

Methods

`  cancel  `

`POST /v1/{name=projects/*/locations/*/operations/*}:cancel`  
Starts asynchronous cancellation on a long-running operation.

`  delete  `

`DELETE /v1/{name=projects/*/locations/*/operations/*}`  
Deletes a long-running operation.

`  get  `

`GET /v1/{name=projects/*/locations/*/operations/*}`  
Gets the latest state of a long-running operation.

`  list  `

`GET /v1/{name=projects/*/locations/*}/operations`  
Lists operations that match the specified filter in the request.

## REST Resource: [v1.projects.locations.serviceProducers](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/projects.locations.serviceProducers)

Methods

`  generateServiceAgents  `

`POST /v1/{parent=projects/*/locations/*/serviceProducers/*}:generateServiceAgents`  
Creates all service agents for a given resource, location and service producer.
