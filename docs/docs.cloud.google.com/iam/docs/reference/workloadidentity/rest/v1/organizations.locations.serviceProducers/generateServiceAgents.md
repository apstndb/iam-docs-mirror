---
name: documents/docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/organizations.locations.serviceProducers/generateServiceAgents
uri: https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/organizations.locations.serviceProducers/generateServiceAgents
title: 'Method: organizations.locations.serviceProducers.generateServiceAgents'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/organizations.locations.serviceProducers/generateServiceAgents#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/organizations.locations.serviceProducers/generateServiceAgents#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/organizations.locations.serviceProducers/generateServiceAgents#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/organizations.locations.serviceProducers/generateServiceAgents#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/organizations.locations.serviceProducers/generateServiceAgents#body.aspect)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/organizations.locations.serviceProducers/generateServiceAgents#try-it)

Creates all service agents for a given resource, location and service producer.

### HTTP request

`POST https://workloadidentity.googleapis.com/v1/{parent=organizations/*/locations/*/serviceProducers/*}:generateServiceAgents`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource. The `location` for the parent resource must be `global` .

Examples:

  - projects/1234/locations/global/serviceProducers/bigquery.googleapis.com
  - folders/2344/locations/global/serviceProducers/vertexai.googleapis.com
  - organizations/3344/locations/global/serviceProducers/iam.googleapis.com

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
