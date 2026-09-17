---
name: documents/docs.cloud.google.com/iam/docs/reference/cloudoauth/rest
uri: https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest
title: Cloud OAuth Service API
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

Provides a unified endpoint for Google Cloud user authentication, exchanging credentials for OAuth 2.0 access tokens.

  - [REST Resource: v1.common](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest#v1.common)
  - [REST Resource: v1.organizations](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest#v1.organizations)

## Service: cloudoauth.googleapis.com

### Service endpoint

A [service endpoint](https://cloud.google.com/apis/design/glossary#api_service_endpoint) is a base URL that specifies the network address of an API service. One service might have multiple service endpoints. This service has the following service endpoint and all URIs below are relative to this service endpoint:

  - `https://cloudoauth.googleapis.com`

## REST Resource: [v1.common](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common)

Methods

`  groups  `

`GET /v1/common/groups`  
Retrieves a list of groups for the authenticated user from the distributed claims endpoint.

`  token  `

`POST /v1/common/token`  
Exchanges a credential for a Google-generated [OAuth 2.0 access token](https://www.rfc-editor.org/rfc/rfc6749#section-5) or [refreshes an access token](https://www.rfc-editor.org/rfc/rfc6749#section-6) following the [OAuth 2.0 Authorization Framework](https://www.rfc-editor.org/rfc/rfc6749) .

`  userinfo  `

`GET /v1/common/userinfo`  
Retrieves claims about the authenticated user from the OIDC /userinfo endpoint.

## REST Resource: [v1.organizations](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations)

Methods

`  token  `

`POST /v1/{parent=organizations/*}/token`  
Exchanges a credential for a Google-generated [OAuth 2.0 access token](https://www.rfc-editor.org/rfc/rfc6749#section-5) or [refreshes an access token](https://www.rfc-editor.org/rfc/rfc6749#section-6) following the [OAuth 2.0 Authorization Framework](https://www.rfc-editor.org/rfc/rfc6749) .

`  userinfo  `

`GET /v1/{parent=organizations/*}/userinfo`  
Retrieves claims about the authenticated user from the OIDC /userinfo endpoint.
