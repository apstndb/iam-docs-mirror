---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest
title: Policy Analyzer API
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [REST Resource: v1.projects.locations.activityTypes.activities](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest#v1.projects.locations.activityTypes.activities)

## Service: policyanalyzer.googleapis.com

### Discovery document

A [Discovery Document](https://developers.google.com/discovery/v1/reference/apis) is a machine-readable specification for describing and consuming REST APIs. It is used to build client libraries, IDE plugins, and other tools that interact with Google APIs. One service may provide multiple discovery documents. This service provides the following discovery document:

  - <https://policyanalyzer.googleapis.com/$discovery/rest?version=v1>

### Service endpoint

A [service endpoint](https://cloud.google.com/apis/design/glossary#api_service_endpoint) is a base URL that specifies the network address of an API service. One service might have multiple service endpoints. This service has the following service endpoint and all URIs below are relative to this service endpoint:

  - `https://policyanalyzer.googleapis.com`

## REST Resource: [v1.projects.locations.activityTypes.activities](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities)

Methods

`  query  `

`GET /v1/{parent=projects/*/locations/*/activityTypes/*}/activities:query`  
Queries policy activities on Google Cloud resources.
