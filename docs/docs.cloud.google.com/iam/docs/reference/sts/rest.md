---
name: documents/docs.cloud.google.com/iam/docs/reference/sts/rest
uri: https://docs.cloud.google.com/iam/docs/reference/sts/rest
title: Security Token Service API
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

The Security Token Service exchanges Google or third-party credentials for a short-lived access token to Google Cloud resources.

  - [REST Resource: v1beta](https://docs.cloud.google.com/iam/docs/reference/sts/rest#v1beta)
  - [REST Resource: v1](https://docs.cloud.google.com/iam/docs/reference/sts/rest#v1)

## Service: sts.googleapis.com

### Discovery document

A [Discovery Document](https://developers.google.com/discovery/v1/reference/apis) is a machine-readable specification for describing and consuming REST APIs. It is used to build client libraries, IDE plugins, and other tools that interact with Google APIs. One service may provide multiple discovery documents. This service provides the following discovery documents:

  - <https://sts.googleapis.com/$discovery/rest?version=v1>
  - <https://sts.googleapis.com/$discovery/rest?version=v1beta>

### Service endpoint

A [service endpoint](https://cloud.google.com/apis/design/glossary#api_service_endpoint) is a base URL that specifies the network address of an API service. One service might have multiple service endpoints. This service has the following service endpoint and all URIs below are relative to this service endpoint:

  - `https://sts.googleapis.com`

## REST Resource: [v1beta](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/TopLevel/token)

Methods

`  token  `

`POST /v1beta/token`  
Exchanges a credential for a Google OAuth 2.0 access token.

## REST Resource: [v1](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/TopLevel/token)

Methods

`  token  `

`POST /v1/token`  
Exchanges a credential for a Google OAuth 2.0 access token.
