---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest
title: Policy Assist API
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

policyassist.googleapis.com API.

  - [REST Resource: v1.projects.locations.global](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest#v1.projects.locations.global)

## Service: policyassist.googleapis.com

To call this service, we recommend that you use the Google-provided [client libraries](https://cloud.google.com/apis/docs/client-libraries-explained) . If your application needs to use your own libraries to call this service, use the following information when you make the API requests.

### Discovery document

A [Discovery Document](https://developers.google.com/discovery/v1/reference/apis) is a machine-readable specification for describing and consuming REST APIs. It is used to build client libraries, IDE plugins, and other tools that interact with Google APIs. One service may provide multiple discovery documents. This service provides the following discovery document:

  - <https://policyassist.googleapis.com/$discovery/rest?version=v1>

### Service endpoint

A [service endpoint](https://cloud.google.com/apis/design/glossary#api_service_endpoint) is a base URL that specifies the network address of an API service. One service might have multiple service endpoints. This service has the following service endpoint and all URIs below are relative to this service endpoint:

  - `https://policyassist.googleapis.com`

## REST Resource: [v1.projects.locations.global](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global)

Methods

`  recommendIamRoles  `

`POST /v1/{parent=projects/*}/locations/global:recommendIamRoles`  
Gets role suggestions for individual principals with AI assistance.
